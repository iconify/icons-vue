<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vf1g9gesw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:quickweather" /></template>
<style>
.vf1g9gesw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.43 17.33c4.46-.24 9.1 2.33 10.64 8.21a6.88 6.88 0 0 1 .05 13.71H11.89c-9.21-1.25-10.47-14.66 0-16.46a10.14 10.14 0 0 1 8.54-5.46m10.7-5.05V8.75m-6.25 6.12l-2.5-2.5m15 15.01l2.5 2.49m.09-8.75h3.53m-6.12-6.25l2.5-2.5m-12.752 4.02a6.2 6.2 0 0 1 8.05.031a6.2 6.2 0 0 1 1.234 7.956");
}

</style>
