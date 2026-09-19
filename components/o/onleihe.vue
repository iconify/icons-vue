<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ydqthzbbt"/><rect transform="rotate(-20 16.155 26.549)" class="t6um1t7kw"/><path class="p78axsbcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:onleihe" /></template>
<style>
.p78axsbcs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m38.5 26.859l-3.38-9.284a5.99 5.99 0 0 0-7.674-3.58h0a5.99 5.99 0 0 0-3.579 7.676l3.38 9.284m-3.38-9.284l-2.048-5.627");
}

.t6um1t7kw {
  width: 11.976px;
  height: 15.868px;
  x: 10.167px;
  y: 18.614px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 5.988px;
  ry: 5.988px;
}

.ydqthzbbt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 42.5h-29c-2.2 0-4-1.8-4-4v-29c0-2.2 1.8-4 4-4h29c2.2 0 4 1.8 4 4v29c0 2.2-1.8 4-4 4");
}

</style>
