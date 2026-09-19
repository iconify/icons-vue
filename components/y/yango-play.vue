<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="vypihob-j"/><rect class="ri-r-qb6b"/><path class="adv0plb5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:yango-play" /></template>
<style>
.adv0plb5n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.46 17.991a2.217 2.217 0 0 0-2.222-2.212h0c-1.228 0-2.223.99-2.223 2.212v2.254c0 1.221.995 2.212 2.223 2.212h0c1.227 0 2.222-.99 2.222-2.212h-2.222m-10.99 0h-2.972m-.736 2.212l2.222-6.678l2.223 6.678m11.385 3.086l-2.222 3.339l-2.223-3.339m2.223 6.678v-3.339m-4.752 1.127h-2.972m-.737 2.212l2.222-6.678l2.223 6.678");
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.ri-r-qb6b {
  width: 4.445px;
  height: 6.678px;
  x: 34.254px;
  y: 15.779px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.222px;
  ry: 2.212px;
}

.vypihob-j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.54 25.543v6.678h3.355m-9.593 0v-6.678h2.196a2.246 2.246 0 0 1 2.248 2.243a2.246 2.246 0 0 1-2.248 2.242H9.302m12.476-7.571v-6.678l4.445 6.678v-6.678m-12.477 0l-2.222 3.339L9.3 15.779m2.224 6.678v-3.339");
}

</style>
