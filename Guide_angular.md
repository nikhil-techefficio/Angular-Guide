## Removal of old CLI
npm uninstall --save-dev @angular/cli@latest
npm uninstall -g @angular/cli


# Add new CLI
npm install --save-dev @angular/cli@latest
npm install -g @angular/cli@latest

# New Version
 Ng version
# Build
 Npm run build
  # Prod
    Npm run build --prod

# New Component
ng g c <component_name>

npm i  @angular/common@18.0.0   

# Best practecis for Ease and good code maintanence 
Maintaining constants to stare the api fetch value.

Saperate Js/Ts files to store Comman constants,
  Struchering of an API .
   --> Api Env file with values assined to variabules.  
      -- sub file /file to maintain /Store jenerated Tocken.  
   -- All end points of Api Publick/Private assined to a variabul,  
   -- Common file js/ts to store all api calles,   
   -- common/ Global file to store Indexes which store current state  
   -- SASS Using full potential of SASS    
         --> Global SASS files which include all --Root /Variabules [Include all Fontfamilts,Background colour,common 
             classes,@importing Other Sass on the whore or respective dependencies]  
   --> 



