<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="wryq7qf1p"/><path class="g9iewmb7q"/><path class="roum1zb8y"/><path class="yjcbf8b5d"/><path class="ts8bjky0l"/><path class="ll0cv8o9n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:wi-fi-router-minimalistic-broken" /></template>
<style>
.g9iewmb7q {
  d: path("M19.3806 8.65811C19.0167 7.41107 17.865 6.5 16.5004 6.5C15.1358 6.5 13.984 7.41107 13.6201 8.65811");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ll0cv8o9n {
  stroke-linejoin: round;
  d: path("M6 16H6.0001");
}

.roum1zb8y {
  d: path("M13 20H6C4.11438 20 3.17157 20 2.58579 19.4142C2 18.8284 2 17.8856 2 16C2 14.1144 2 13.1716 2.58579 12.5858C3.17157 12 4.11438 12 6 12H18C19.8856 12 20.8284 12 21.4142 12.5858C22 13.1716 22 14.1144 22 16C22 17.8856 22 18.8284 21.4142 19.4142C20.8284 20 19.8856 20 18 20H17");
}

.ts8bjky0l {
  stroke-linejoin: round;
  d: path("M9 16H9.0001");
}

.wryq7qf1p {
  d: path("M21.5833 7.39702C20.7574 5.40286 18.7924 4 16.4996 4C14.2069 4 12.2419 5.40286 11.416 7.39702");
}

.yjcbf8b5d {
  d: path("M16.5 12V9");
}

</style>
