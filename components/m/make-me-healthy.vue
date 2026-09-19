<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z_u64mb7s"/><path class="fcu4tfick"/><path class="avy9ifbmo"/><path class="pov-zsbwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:make-me-healthy" /></template>
<style>
.avy9ifbmo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.69 34.891c6.674 3.825 18.089 2.586 19.028-8.465c.923-10.854-2.42-10.475-3.087-15.79c-5.095 1.663-14.97-.793-20.048 8.186c-3.909 6.912-1.395 12.915 4.108 16.07");
}

.fcu4tfick {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.631 10.635C20.955 26.271 12.583 42.216 12.583 42.216");
}

.pov-zsbwi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.444 22.563c-3.12.135-5.444.479-5.444.479c0-2.626-.965-5.612-.965-5.612m-4.093 4.865c.805 2.986 1.187 6.86 1.187 6.86c3.342-.989 7.47-1.09 7.47-1.09");
}

.z_u64mb7s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.779 2.536C10.924 3.21 1.86 13.366 2.535 25.22c.675 11.856 10.832 20.92 22.686 20.244");
}

</style>
