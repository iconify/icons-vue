<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ydqthzbbt"/><path class="tbo-6k-1s"/><rect class="qq13lqbbx"/><path class="zn8uu0sya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:varo-bank" /></template>
<style>
.qq13lqbbx {
  width: 4.771px;
  height: 6.321px;
  x: 30.839px;
  y: 22.45px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.385px;
  ry: 2.385px;
}

.tbo-6k-1s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m18.711 19.23l-3.16 9.54l-3.161-9.54");
}

.ydqthzbbt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 42.5h-29c-2.2 0-4-1.8-4-4v-29c0-2.2 1.8-4 4-4h29c2.2 0 4 1.8 4 4v29c0 2.2-1.8 4-4 4");
}

.zn8uu0sya {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.726 24.835a2.385 2.385 0 0 1 2.385-2.385h0m-2.385 0v6.32m-2.436-2.385a2.385 2.385 0 0 1-2.386 2.386h0a2.385 2.385 0 0 1-2.385-2.386v-1.55a2.385 2.385 0 0 1 2.385-2.385h0a2.385 2.385 0 0 1 2.386 2.385m0 3.935v-6.32");
}

</style>
