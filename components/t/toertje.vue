<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="znsc9k_zy"/><path class="lq_a98bqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:toertje" /></template>
<style>
.lq_a98bqi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.34 20h13.674S28.03 33.196 28 33.66");
}

.znsc9k_zy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M45.12 28H33.66l8.11 8.11c-.76 1.11-1.62 2.14-2.57 3.09s-1.98 1.81-3.09 2.57L28 33.66v11.46c-1.29.25-2.63.38-4 .38s-2.71-.13-4-.38V33.66l-8.11 8.11c-1.11-.76-2.14-1.62-3.09-2.57s-1.81-1.98-2.57-3.09L14.34 28H2.88c-.25-1.29-.38-2.63-.38-4s.13-2.71.38-4h11.46l-8.11-8.11c.76-1.11 1.62-2.14 2.57-3.09s1.98-1.81 3.09-2.57L20 14.34V2.88c1.29-.25 2.63-.38 4-.38s2.71.13 4 .38v11.46l8.11-8.11c1.11.76 2.14 1.62 3.09 2.57s1.81 1.98 2.57 3.09L33.66 20h11.46c.25 1.29.38 2.63.38 4s-.13 2.71-.38 4");
}

</style>
