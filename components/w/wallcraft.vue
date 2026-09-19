<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i4etjbheb"/><path class="gtqrm54cf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wallcraft" /></template>
<style>
.gtqrm54cf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m33.5 16l-4.75 16L24 16l-4.75 16l-4.75-16");
}

.i4etjbheb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.62 34.75L24 45.5L5.38 34.75v-21.5L24 2.5l18.62 10.75z");
}

</style>
