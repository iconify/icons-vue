<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="wryq7qf1p"/><path class="g9iewmb7q"/><path class="os6rdo5dh"/><path class="yjcbf8b5d"/><path class="ts8bjky0l"/><path class="ll0cv8o9n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:wi-fi-router-minimalistic-linear" /></template>
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

.os6rdo5dh {
  d: path("M6 20H18C19.8856 20 20.8284 20 21.4142 19.4142C22 18.8284 22 17.8856 22 16C22 14.1144 22 13.1716 21.4142 12.5858C20.8284 12 19.8856 12 18 12H6C4.11438 12 3.17157 12 2.58579 12.5858C2 13.1716 2 14.1144 2 16C2 17.8856 2 18.8284 2.58579 19.4142C3.17157 20 4.11438 20 6 20Z");
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
