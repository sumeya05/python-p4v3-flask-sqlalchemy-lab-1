# TODO List for Flask-SQLAlchemy Lab 1

- [ ] Fix the magnitude filter in server/app.py to use >= instead of exact match
- [ ] Initialize the database: cd server && flask db init
- [ ] Create migration: cd server && flask db migrate -m "initial migration"
- [ ] Upgrade database: cd server && flask db upgrade head
- [ ] Seed the database: cd server && python seed.py
- [ ] Run models tests: cd server && pytest testing/models_test.py
- [ ] Run earthquake route tests: cd server && pytest testing/app_earthquake_test.py
- [ ] Run magnitude route tests: cd server && pytest testing/app_magnitude_test.py
- [ ] Run all tests: cd server && pytest
