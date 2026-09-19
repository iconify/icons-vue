<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jg0yogb4f"/><ellipse transform="rotate(-73.52 33.944 33.481)" class="gmldv77do"/><ellipse transform="rotate(-73.52 41.068 30.77)" class="bwlnbbbab"/><path class="j3b4x5bem"/><path class="jxwblkbwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:viabus" /></template>
<style>
.bwlnbbbab {
  cx: 41.068px;
  cy: 30.771px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.211px;
  ry: 0.953px;
}

.gmldv77do {
  cx: 33.944px;
  cy: 33.481px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.211px;
  ry: 0.953px;
}

.j3b4x5bem {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.41 28.142c-.038-.837.193-1.594.613-2.086c-1.11-1.17-2.355.375-2.307 1.481L4.5 26.724V14.978l12.264-4.521l23.747 8.621c3.512 1.276 2.57 3.637 2.989 13.705l-11.068 4.081l-2.645-.96");
}

.jg0yogb4f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.68 16.333v5.517l24.457 9.02l-.465-5.918zm26.127 8.973l.408 5.47l8.228-3.142l-.335-5.46z");
}

.jxwblkbwk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.558 29.649c-.205.836-.714 1.465-1.412 1.614c-1.123.24-2.309-.855-2.649-2.445a4 4 0 0 1-.087-.676m15.542 5.644l-11.396-4.138m17.238 6.249c-.204.836-.714 1.465-1.412 1.614c-1.123.24-2.309-.855-2.648-2.445a4 4 0 0 1-.088-.676c-.038-.837.193-1.594.614-2.086c-1.11-1.17-2.356.375-2.308 1.481m5.842 2.112c-.204.836-.714 1.465-1.412 1.614c-1.123.24-2.309-.855-2.648-2.445a4 4 0 0 1-.088-.676c-.038-.837.193-1.594.614-2.086");
}

</style>
