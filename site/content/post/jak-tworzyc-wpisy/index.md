---
title: Jak utworzyć nowy wpis w sekcji "Z życia kręgu"?
date: 2017-01-04T15:04:10.000Z
description: Artykuł prezentuje w jaki tworzyć nowe strony w sekcji Z życia kręgu. Sekcja ta wyświetla wpisy w kolejności chronologicznej oraz umożliwia prezentację skrótów (opisów) na innych podstronach.
image: question-mark.jpg
author: Wojciech Sroczyński
---

## Wstep

System używa komponentów CMS, które pozwalają na edycję strony w sposób podobny do wordpressa, ale bez użycia bazy danych. Pozwala to na zmniejszenie kosztów hostingu, przy zachowaniu podstawowej edycji.
Artykuł opisuje działają wpisy w sekcji [Z życia kręgu](/post)

## Jakie dane są zapisywane:

Zastosowane do budowy strony komponenty wymagają, aby każdy wpis posiadał ustandaryzowaną postać. Oznacza to, że każdy nowy artykuł z tej sekcji ma listę pól, które mogą być użyte do budowy treści.
Dzięki takiej standaryzacji, uprawnieni użytkownicy mogą mieć możliwość edycji strony w sekcja administracyjnej.

Lista dostępnych pól:

1. Tytuł: krótki tekst, wyświetlany w samym artykule ale również na liście wpisów. Wymagany
2. Data wpisu: używana do sortowania wpisów i wybierania podzbioru do listy ostatnich wpisów. Wymagana
4. Autor: Opcjonalny, ale zalecany przy kilku osobach tworzących stronę
3. Opis: Krótki opis artykułu, pojawia się na liście ostatnich wpisów, przydatny dla gościa strony do szybkiej oceny czy chce otwierać artykuł. Wymagany.
4. Treść artykułu: Wymagana
5. Ikonka lub zdjęcie: Prezentowany na liście artykułów. Opcjonalny, ale przydatny do zapewnienia jednorodnego wyglądu.

## Technikalia

Artykułu zapisywane są na serwerze w folderze \site\content\post\, każdy w nowym folderze. 