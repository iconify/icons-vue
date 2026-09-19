<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="conl0vbct"/><path class="ggwwm0b8e"/><path class="yd-ozy1ie"/><path class="l_9yj_bul"/><path class="sawwzntif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:recyclecoach" /></template>
<style>
.conl0vbct {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M2.5 24.5c7.442 0 14.503-2.071 19.625-7.193c5.12-5.12 5.877-12.399 13.117-12.695c-9.138-5.877-18.956 2.02-24.438 11.465");
}

.ggwwm0b8e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.363 2.5C10.506 2.5 2.5 13.64 2.5 24.501M36.75 6.422c3.13 1.808 7.813 6.157 8.75 9.655c-5.247 1.406-11.837 1.808-18.103-1.81");
}

.l_9yj_bul {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.637 45.5C37.494 45.5 45.5 34.36 45.5 23.499M11.25 41.578C8.12 39.77 3.438 35.42 2.5 31.923c5.247-1.406 11.837-1.808 18.103 1.81");
}

.sawwzntif {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.183 38.873c-.846-.227-3.595-1.482-4.235-2.123");
}

.yd-ozy1ie {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.817 9.127c.846.226 3.595 1.482 4.235 2.123M45.5 23.499c-7.441 0-14.503 2.072-19.624 7.193c-5.122 5.121-5.877 12.4-13.118 12.696c9.139 5.877 18.956-2.02 24.438-11.465");
}

</style>
