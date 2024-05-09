# Installation

### Step 1: Create required directories for laravel framework
```bash
mkdir -p storage/framework/cache storage/framework/views storage/framework/sessions storage/framework/testing
```

### Step 2: Install composer dependencies
```bash
   composer install
```

### Step 3: Create .env file
```bash
   cp .env.example .env
```

### Step 4: Generate Keys (this will update you .env file)
```bash
   php artisan key:generate
```

### Step 5: Migrate database
```bash
   php artisan migrate
```

### Step 6: Seed database
```bash
   php artisan db:seed
```

### Step 7: Install dependencies for frontend
```bash
   npm install
```

### Step 8: Build frontend
```bash
   npm run dev
```

### Step 9: Run the application
```bash
   php artisan serve
```

## Step 10: Visit the application
```bash
   http://localhost:8000
```