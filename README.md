# backup
- Automated backup using rsync.<br />
- Run it daily using cron job.<br />
- Creates a new full backup every sunday and a differential backup every day until next sunday.<br />
- Old backups will be removed if low on space.<br />
- Requires bc command to calculate available space.
