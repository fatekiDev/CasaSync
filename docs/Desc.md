# Nombre: CasaSync

## Objetivo:

CasaSync será una aplicación web donde varias personas puedan colaborar para administrar un hogar.

Ejemplos:

Familia
Pareja
Roommates
Casa de vacaciones

## Tecnologias
- Fronted: Flutter
- Backend: Supabase
- DataBase: PostgreSQL
- Versions Control: GitHub
- Desing: Figma

## Arquitectura
Flutter
    |
    |
Supabase
    |
    |
PostgreSQL

## Estructura de Datos Inicial:


### users

id
email
created_at

### homes
id
name
created_by
created_at

### home_members
id
home_id
user_id

### rooms
id
home_id
name

### items
id
room_id
title
description
status
price

### expenses
id
home_id
month
year
amount
category