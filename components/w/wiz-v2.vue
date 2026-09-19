<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z4u1xcb3z"/><path class="azk3aacae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wiz-v2" /></template>
<style>
.azk3aacae {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.802 22.054c2.515 3.306 3.055 7.136 2.957 11.134");
}

.z4u1xcb3z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m27.96 43.5l-7.032-.13m6.967-3.394l-7.296-.13c-2.391-.044-2.44-3.748 0-3.721l5.85.065c1.404.016 2.13-.745 2.214-3.459c.204-6.572 2.712-9.615 4.818-14.032h-19.87C10.097.722 34.893.092 34.73 15.239");
}

</style>
