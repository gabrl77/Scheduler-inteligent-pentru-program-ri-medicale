# Scheduler-inteligent-pentru-programari-medicale

Tehnologia pe care vrem sa o folosim este Python, PyQt6(pentru interfata grafica), SQLite(pentru baza de date), SQLAlchemy, Matplotlib, PyInstaller, Plyer

Structura directoarelor
```medischeduler/
├── main.py
├── requirements.txt
├── config.py
├── database/
│   ├── sqlalchemy.py
│   ├── db.py
│   └── dateslot.py
├── logic/
│   ├── calendar.py
│   ├── urgenta.py
│   ├── sugestie.py
│   └── notificari.py
├── ui/
│   ├── main_window.py
│   ├── calendar_widget.py
│   ├── dialog_pacienti.py
│   ├── lista_asteptare.py
│   └── stats_panel.py
```
```
Baza de date schema
pacienti                 id, nume, cnp, phone, nastere
programari               id, pacienti_id, slot_id, type, stare
sloturi                  id, date, start_time, duration_min
lista_asteptare          id, pacienti_id, data_preferata, type
notificari               id, programari_id, send_at, type
```
```
Roadmap 12 Martie ->  30 Aprilie 2026
1. 12-23 Martie   github, db, sqlachemy,
2. 24 Martie - 4 Aprilie  UI: calendar, sloturi, programare
3. 7-18 Aprilie  functii: urgente, asteptare, sugestie
4. 21-30 Aprilie  testare, rezolvare de probleme, si build-ul final
```
```
Milestones                                                                  DATA TINTA
1. db creat si functionarea bazalor de date                                 23 Martie
2. fereastra principala si calendar                                         28 Martie
3. programari                                                                4 Aprilie
4. urgente si decalare automata                                             11 Aprilie
5. lista de asteptare si sugestie slot                                      18 Aprilie
6. notificari si statistice                                                 23 Aprilie
7. testare si creare de .exe                                                30 Aprilie
```

            ACEASTA SCHITA SE POATE MODIFICA USOR



