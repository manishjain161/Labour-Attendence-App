# Labour Attendance App Starter

Scope: workers, contractors, categories, sites, site assignments, attendance, GPS fields.

Production flow:
Face scan -> liveness -> GPS/geofence -> worker/site check -> IN/OUT -> database.

This starter does not perform real biometric recognition yet. A face provider and secure backend must be connected before production. Do not store raw face images publicly.

Run `sql/schema.sql` in a PostgreSQL database. Then connect the web app through a secure backend/API.
