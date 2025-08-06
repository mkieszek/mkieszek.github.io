---
layout: case-study
title: "Wdrożenie zdalnego dostępu do Symfonii dla działu księgowości"
client: "Dział księgowości firmy produkcyjnej"
tags: ["Symfonia", "VPN", "SQL Server", "Zdalna praca"]
---

# Wdrożenie zdalnego dostępu do Symfonii dla działu księgowości

## Wyzwanie

Klient potrzebował profesjonalnego rozwiązania do zarządzania systemem Symfonia 2025 dla 5-osobowego działu księgowości. Główne problemy do rozwiązania:

- Baza danych znajdowała się na pojedynczym komputerze księgowej
- Brak możliwości jednoczesnej pracy wielu użytkowników
- Niski poziom zabezpieczenia danych księgowych
- Rozproszona lokalizacja pracowników wymagających dostępu do systemu

## Rozwiązanie

Wdrożyliśmy kompleksowe rozwiązanie serwerowe z bezpiecznym dostępem zdalnym:

### Infrastruktura serwerowa
- Instalacja Microsoft SQL Server 2019 Express
- Wdrożenie Symfonia 2025 w wersji sieciowej
- Konfiguracja sprzętowego RAID 1 dla bezpieczeństwa danych
- Podłączenie serwera do zasilania awaryjnego (UPS)

### Dostęp zdalny
- Konfiguracja routera Draytek z VPN SSL
- Wdrożenie bezpiecznych połączeń dla 5 stanowisk
- Konfiguracja klientów Symfonii na komputerach użytkowników

### Bezpieczeństwo danych
- Implementacja systemu kopii zapasowych
- Redundancja dysków (RAID 1)
- Zabezpieczenie przed utratą zasilania
- Bezpieczny dostęp przez szyfrowany tunel VPN

## Proces wdrożenia

Całe wdrożenie zostało zrealizowane w ciągu 3 dni:

1. Dzień 1: Instalacja i konfiguracja serwera
   - Konfiguracja RAID 1
   - Instalacja SQL Server 2019 Express
   - Migracja bazy danych Symfonii

2. Dzień 2: Konfiguracja dostępu zdalnego
   - Instalacja i konfiguracja VPN na routerze Draytek
   - Testy połączeń i wydajności

3. Dzień 3: Wdrożenie na stacjach klienckich
   - Konfiguracja oprogramowania na komputerach użytkowników
   - Szkolenie pracowników
   - Testy końcowe

## Korzyści dla klienta

1. **Zwiększone bezpieczeństwo danych**
   - Redundancja dzięki RAID 1
   - Regularne kopie zapasowe
   - Zabezpieczenie przed awarią zasilania

2. **Usprawnienie pracy**
   - Możliwość jednoczesnej pracy 5 użytkowników
   - Dostęp do systemu z dowolnej lokalizacji
   - Szybsza i wydajniejsza praca zespołowa

3. **Profesjonalna infrastruktura**
   - Centralne zarządzanie bazą danych
   - Stabilne i bezpieczne połączenia VPN
   - Możliwość rozbudowy systemu

## Użyte technologie

- Serwer baz danych: Microsoft SQL Server 2019 Express
- System finansowo-księgowy: Symfonia 2025
- VPN: Draytek SSL VPN
- Zabezpieczenia: RAID 1, UPS
- Backup: Automatyczne kopie zapasowe

## Wnioski

Projekt pokazał, jak ważne jest profesjonalne podejście do infrastruktury IT w księgowości. Dzięki wdrożeniu:
- Znacząco zwiększyło się bezpieczeństwo danych
- Umożliwiono pracę zdalną
- Zapewniono skalowalność rozwiązania

To case study demonstruje, że nawet stosunkowo niewielkie działy księgowe mogą korzystać z profesjonalnych rozwiązań serwerowych, zapewniających zarówno bezpieczeństwo danych, jak i wygodę pracy.
