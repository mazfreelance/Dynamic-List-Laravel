# Dynamic-List-Laravel
How to make dynamic list in laravel
1. Create model 
   php artisan make:model modelNameFile

2. Create provider
   php artisan make:provider providerNameFile 
   
3. Update file 'config/app.php'. Search words 'Ap\Provider\'.
   Copy & paste 'App\Providers\NameProvider::class
   
4. On views file
   Copy & paste the code:
   @foreach($arrayname as $value)
    {{ $value->Columntable }}
   @endforeach

example code: https://gist.github.com/mazfreelance/0f00c41a1a9f11358bf87a5878a0a945
