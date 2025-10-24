# Quick Start Guide

## 5-Minute Setup

### 1. Extract & Configure

```bash
cp wp-config-sample.php wp-config.php
```

### 2. Create Database

```sql
CREATE DATABASE wordpress_zoho;
CREATE USER 'wp_user@''localhost' IDENTIFIED BY 'secure_password';
GRANT ALL ON wordpress_zoho.* TO 'wp_user'@'localhost';
FLUSH PRIVILEGES;
```

### 3. Run Installer

Visit: `http://yoursite.com/wp-admin/install.php`

### 4. Activate Theme
- Go to Appearance ‚ö Themes
- Activate "Zoho Custom Theme"

### 5. Import Content
- Go to Tools ‚Å†Zoo Importer
- Click "Import Zoho Content"

Done! Your site is ready.