<template>
  <v-app class="bg-white">
   <v-container class="text-center">
   <h1 class="text-h1">BUTTON COMPONENT</h1>
     <v-row>
       <v-col cols="auto">
       <v-btn density="default">default</v-btn>
       </v-col>
       <v-col cols="auto">
       <v-btn density="compact">compact</v-btn>
       </v-col>
       <v-col cols="auto">
       <v-btn density="comfortable">comfortable</v-btn>
       </v-col>
     </v-row>
  
  
  
  
     <v-row>
     <v-col cols="auto">
     <v-btn size="x-small">EXTRA SMALL BUTTON</v-btn>
     </v-col>
     <v-col cols="auto">
     <v-btn size="small">SMALL BUTTON</v-btn>
     </v-col>
     <v-col cols="auto">
     <v-btn>BUTTON</v-btn>
     </v-col>
     <v-col cols="auto">
     <v-btn size="large">LARGE BUTTON</v-btn>
     </v-col>
     <v-col cols="auto">
     <v-btn size="x-large">EXTRA LARGE BUTTON</v-btn>
     </v-col>
     </v-row>
  
  
  
  
     <v-row align-center justify-center>
     <v-btn block>BLOCK</v-btn>
     </v-row>
  
  
   <v-row>
   <v-col cols="12" md="4" sm="6">
   <v-btn rounded="0" size="x-large" block>rounded 0</v-btn>
   </v-col>
   <v-col cols="12" md="4" sm="6">
   <v-btn rounded="xs" size="x-large" block>rounded xs</v-btn>
   </v-col>
   <v-col cols="12" md="4" sm="6">
   <v-btn rounded="sm" size="x-large" block>rounded sm</v-btn>
   </v-col>
   <v-col cols="12" md="4" sm="6">
   <v-btn size="x-large" block>default</v-btn>
   </v-col>
   <v-col cols="12" md="4" sm="6">
   <v-btn rounded="lg" size="x-large" block>rounded lg</v-btn>
   </v-col>
   <v-col cols="12" md="4" sm="6">
   <v-btn class="rounded-xl" size="x-large">rounded xl</v-btn>
   </v-col>
   </v-row>
  
  
   <v-row>
   <v-col cols="auto">
   <v-btn size="x-large">default elevation (2)</v-btn>
   </v-col>
   <v-col cols="auto">
   <v-btn elevation="4" size="x-large">elevation 4</v-btn>
   </v-col>
   <v-col cols="auto">
   <v-btn elevation="8" size="x-large">elevation 8</v-btn>
   </v-col>
   <v-col cols="auto">
   <v-btn elevation="12" size="x-large">elevation 12</v-btn>
   </v-col>
   <v-col cols="auto">
   <v-btn elevation="16" size="x-large">elevation 16</v-btn>
   </v-col>
   <v-col cols="auto">
   <v-btn elevation="20" size="x-large">elevation 20</v-btn>
   </v-col>
   <v-col cols="auto">
   <v-btn elevation="24" size="x-large">elevation 24</v-btn>
   </v-col>
   </v-row>
  
  
  
  
   <v-row>
   <v-col cols="auto">
   <v-btn icon="mdi-plus" size="x-small"></v-btn>
   </v-col>
   <v-col cols="auto">
   <v-btn icon="$vuetify" size="x-small"></v-btn>
   </v-col>
   <v-col cols="auto">
   <v-btn icon="mdi-open-in-new" size="x-small"></v-btn>
   </v-col>
   <v-col cols="auto">
   <v-btn icon="mdi-account" size="x-small"></v-btn>
   </v-col>
   <v-col cols="auto">
   <v-btn icon="mdi-calender" size="x-small"></v-btn>
   </v-col>
   </v-row>
  
  
   </v-container>
  
  
   <v-container class="d-flex justify-center">
     <v-card class="mx-auto" max-width="450" title="Strengthen your passwords" text="Update your weak or re-used passwords with Password Checkup. It's free and only takes a few minutes. Click the Take Checkup button to get started.">
     <template v-slot:actions>
     <v-btn height="48" rounded>no thanks</v-btn>
     <v-btn :loading="loading" class="flex-grow-1" height="48" variant="tonal" @click="load">Take checkup</v-btn>
     </template>
     </v-card>
   </v-container>
  
  
   <v-container>
   <h1 class="text-h1">CARD COMPONENT</h1>
  
  
   <v-card title="This is a title" subtitle="This is a card subtitle" text="Lorem ipsum dolor sit amet consectetur adipisicing elit. Commodi, ratione debitis quis est labore voluptatibus!">
   </v-card>
  </v-container>
  
  
  
  
  
  
  <v-container>
  <v-card class="mx-auto"
  append-icon="mdi-open-in-new"
  prepend-icon="mdi-github"
  title="Vuetify on GitHub"
  text="Check out the official repository"
  hover></v-card>
  </v-container>
  
  
  <v-container>
         <v-card class="mx-auto">
           <v-img height="250px" src="https://cdn.vuetifyjs.com/images/cards/sunshine.jpg" cover></v-img>
           <v-card-title>Top Western road trips</v-card-title>
           <v-card-subtitle>1,000 miles of wonder</v-card-subtitle>
           <v-card-actions>
             <v-btn color="orange-lighten-2">Explore</v-btn>
             <v-spacer></v-spacer>
             <v-btn :icon="show ? 'mdi-chevron-up' : 'mdi-chevron-down'" @click="show = !show"></v-btn>
           </v-card-actions>
           <v-expand-transition>
             <div v-show="show">
               <v-divider></v-divider>
               <v-card-text>
                 I'm a thing. But, like most politicians, he promised more than he
           could deliver. You won't have time for sleeping, soldier, not with all
           the bed making you'll be doing. Then we'll go with that data file!
           Hey, you add a one and two zeros to that or we walk! You're going to
           do his laundry? I've got to find a way to escape.
               </v-card-text>
             </div>
           </v-expand-transition>
         </v-card>
       </v-container>
  
  
  
  
  
  
  <v-container>
  <v-card class="mx-auto" max-width="400">
  <v-img src="https://cdn.vuetifyjs.com/images/cards/docks.jpg" height="200" class="align-end text-white" cover>
  <v-card-title>Top 10 Australian Beaches</v-card-title></v-img>
  <v-card-subtitle>Number 10</v-card-subtitle>
  <v-card-text>
       <div>Whitehaven Beach</div>
  
  
       <div>Whitsunday Island, Whitsunday Islands</div>
     </v-card-text>
  
  
     <v-card-actions>
       <v-btn color="orange" text="Share"></v-btn>
  
  
       <v-btn color="orange" text="Explore"></v-btn>
     </v-card-actions>
  </v-card>
  </v-container>
  
  
  <v-container>
   <h1 class="text-h1">CHIPS COMPONENT</h1>
   <v-chip closable prepend-icon="$vuetify" append-icon="$vuetify">chip</v-chip>
   <v-chip draggable>Draggable</v-chip>
   <v-chip prepend-icon="$vuetify" color="orange"></v-chip>
   <v-chip color="primary">primary</v-chip>
   <v-chip color="secondary">secondary</v-chip>
   <v-chip color="red">red</v-chip>
   <v-chip color="green">green</v-chip>
   <v-chip color="primary" variant="flat">primary</v-chip>
   <v-chip color="secondary" variant="flat">secondary</v-chip>
  </v-container>
  
  
  
  
  
  
  <v-container>
  <v-card class="mx-auto" max-width="450">
  <v-img src="https://cdn.vuetifyjs.com/images/cards/house.jpg" cover></v-img>
  <v-card-title>Welcome Home...</v-card-title>
  <v-card-subtitle>Monday,12:30 PM,Mostle Sunny</v-card-subtitle>
  <v-avatar size="24"><v-img src="https://cdn.vuetifyjs.com/images/weather/part-cloud-48px.png" contain></v-img></v-avatar>
  <v-divider></v-divider>
  <v-card-text class="d-flex justify-space-between">
  <v-chip prepend-icon="mdi-brightness" @click="lights">Turn on lights</v-chip>
  <v-chip prepend-icon="mdi-alarm-check" @click="alarm">Set alarm</v-chip>
  <v-chip prepend-icon="mdi-blinds" @click="blinds">Close blinds</v-chip>
  </v-card-text>
  </v-card>
  </v-container>
  
  
  <v-file-input label="file input"></v-file-input>
  
  
  <v-container>
  <v-list lines="one">
  <v-list-items v-for="n in 3" :key="n"><v-card-title>item {{ n }}<v-card-subtitle>Lorem ipsum dolor sit amet consectetur adipisicing elit</v-card-subtitle></v-card-title></v-list-items>
  </v-list>
  </v-container>
  
  
  
  
  <v-container>
  <v-card>
  <v-list>
  <v-list-subheader>Today</v-list-subheader>
  <v-list-item prepend-avatar="https://cdn.vuetifyjs.com/images/lists/1.jpg"
  title="Brunch this weekend?">
  <template v-slot:subtitle>
  <span class="font-weight-bold">Aliconnors</span>&mdash; I'll be in
  your neighborhood doing errands this weekend.
  </template>
  </v-list-item>
  <v-divider></v-divider>
  <v-list-item prepend-avatar="https://cdn.vuetifyjs.com/images/lists/2.jpg"
  title="Brunch this weekend?">
  <template v-slot:subtitle>
  <span class="font-weight-bold">Aliconnors</span>&mdash; I'll be in
  your neighborhood doing errands this weekend.
  </template>
  </v-list-item>
  <v-divider></v-divider>
  <v-list-item prepend-avatar="https://cdn.vuetifyjs.com/images/lists/3.jpg"
  title="Brunch this weekend?">
  <template v-slot:subtitle>
  <span class="font-weight-bold">Aliconnors</span>&mdash; I'll be in
  your neighborhood doing errands this weekend.
  </template>
  </v-list-item>
  </v-list>
  </v-card>
  </v-container>
  
  
  
  
  <v-container justify-center align-center>
   <div class="text-center pa-4">
     <v-btn @click="dialog=true">open dialog</v-btn>
  
  
     <v-dialog v-model="dialog" width="auto" persistent>
       <v-card
      max-width="400" prepend-icon="mdi-update"  text="Your application will relaunch automatically after the update is complete."
       title="Update in progress">
     <template v-slot:actions>
       <v-btn class="ms-auto" text="ok" @click="dialog=false"></v-btn>
     </template></v-card>
     </v-dialog>
   </div>
  </v-container>
  <v-breadcrumbs :items="['foo','bar','fizz']"></v-breadcrumbs>
  <v-pagination :length="4" rounded></v-pagination>
  <v-checkbox label="checkbox"></v-checkbox>
  <v-slider></v-slider>
  <v-container>
  
  
  
  
  </v-container>
  </v-app> 
  </template>
  
  
  
  
  <script setup>
  import { ref } from 'vue';
  
  
  
  
  const dialog=ref(false)
  const show=ref(false)
  const loading=ref(false)
  
  
  const load=() =>{
   loading.value=true
   setTimeout(() => {
     loading.value=false
   }, 3000);
  }
  
  
  const alarm=() =>{
   alert('Turning on alarm')
  }
  
  
  const blinds=() =>{
   alert('Toggling blinds')
  }
  
  
  const lights=() =>{
   alert('Toggling lights')
  }
  </script>
  
  