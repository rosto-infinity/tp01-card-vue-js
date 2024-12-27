<template>
  <div class=" min-h-screen justify-center items-center bg-slate-300"> 
       <div class="max-w-[1200px] w-full py-24 mx-auto mt-32 flex flex-col items-center shadow-lg rounded-xl bg-white">

       <h1 class="s">Select your role</h1>
       
       </div>
  </div>
</template>


  <script setup>
  import { ref } from 'vue'
  const count = ref(0);

  const increment = () => {
    count.value++;
  }
  
  </script>.gitattribute
