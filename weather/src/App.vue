<script setup>
  
  import CardSearch from './components/card-search.vue'
  import CardButton from './components/card-button.vue'
  import CardWeather from './components/card-weather.vue'
  import CardHumidity from './components/card-humidity.vue'
  import CardWind from './components/card-wind.vue'
  import './app.js'

</script>

<template>

  <div class="card">

    <div class="search">
      <CardSearch></CardSearch>
      <CardButton></CardButton>
    </div>

    <div class="weather">
      <CardWeather></CardWeather>
      <div class="details">
        <CardHumidity></CardHumidity>
        <CardWind></CardWind>
      </div> 
    </div>

  </div>

</template>