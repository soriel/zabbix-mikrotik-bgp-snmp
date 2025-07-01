# Zabbix Template: Mikrotik BGP Peer Discovery via SNMP

## 🇷🇺 Описание на русском

Этот шаблон Zabbix предназначен для мониторинга BGP peer'ов на устройствах Mikrotik с использованием SNMP. Он автоматически обнаруживает BGP соединения и создает триггеры для контроля их доступности.

### Возможности:
- Автоматическое обнаружение BGP peer;
- Создание элементов данных для каждого соединения;
- Генерация триггеров при недоступности peer;

### Требования:
- Устройство Mikrotik с включенным SNMP;
- Доступ к SNMP OID, связанным с BGP;
- Zabbix версии 7.0 или выше.

### Установка:
1. Импортируйте файл `zabbix-mikrotik-bgp-snmp.yaml` через веб-интерфейс Zabbix.
2. Назначьте шаблон нужному хосту Mikrotik.
3. Убедитесь, что SNMP работает корректно и Zabbix получает данные.

---

## 🇬🇧 English Description

This Zabbix template is intended for monitoring BGP peers on Mikrotik devices using SNMP. It automatically discovers BGP connections and creates triggers to monitor their availability.

### Features:
- Automatic discovery of BGP peers;
- Creation of data items for each connection;
- Trigger generation on peer unavailability;

### Requirements:
- Mikrotik device with SNMP enabled;
- Access to SNMP OIDs related to BGP;
- Zabbix version 7.0 or higher.

### Installation:
1. Import the `zabbix-mikrotik-bgp-snmp.yaml` file through the Zabbix web interface.
2. Attach the template to your Mikrotik host.
3. Ensure SNMP is properly configured and data is received by Zabbix.

---

## 📁 Файл шаблона

Файл `zabbix-mikrotik-bgp-snmp.yaml` содержит экспорт шаблона Zabbix и должен быть импортирован в интерфейсе Zabbix.

---

## 🛠 Поддержка и улучшения

PR и предложения приветствуются! Если вы сталкиваетесь с проблемами или хотите внести улучшения — создайте issue или pull request.
