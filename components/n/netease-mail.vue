<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a_vx_o--h"/><path class="ji9wgbz0k"/><path class="p7_c_rbrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:netease-mail" /></template>
<style>
.a_vx_o--h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.566 5.308v28.379M9.768 23.49h13.255m5.183-13.17v26.425H4.84");
}

.ji9wgbz0k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 39.464V12.023h23.67m5.983 30.669V12.954a3.555 3.555 0 0 1 3.23-3.144H43.5");
}

.p7_c_rbrr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.558 23.83h3.994c.75 0 .948-1.155.948-1.87V7.857m0 17.503v8.582a3.206 3.206 0 0 1-3.059 3.143h-6.287m4.404-13.255h3.872c.785 0 1.079.912 1.07 1.53");
}

</style>
