<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="mv437_bez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:opencomicvine" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.mv437_bez {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m36.404 19l-5.075 10l-1.55-10m-2.591 6.647l-.007.04C26.858 27.518 25.113 29 23.284 29c-1.83 0-3.051-1.483-2.728-3.312l.595-3.375c.322-1.83 2.067-3.313 3.896-3.313c1.83 0 3.051 1.483 2.729 3.313l-.008.04M14.376 29zc-1.83 0-3.051-1.483-2.729-3.312l.595-3.375C12.565 20.483 14.31 19 16.14 19s3.05 1.483 2.728 3.313l-.595 3.375C17.95 27.517 16.205 29 14.376 29");
}

</style>
