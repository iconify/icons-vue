<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ydqthzbbt"/><rect class="gr_1_obge"/><rect class="yc09wh2nt"/><rect class="wrt4qob1b"/><path class="x76d897qj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:zooforzotero" /></template>
<style>
.gr_1_obge {
  width: 5.687px;
  height: 7.535px;
  x: 21.781px;
  y: 15.339px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.844px;
  ry: 2.844px;
}

.wrt4qob1b {
  width: 5.687px;
  height: 7.535px;
  x: 30.257px;
  y: 28.965px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.844px;
  ry: 2.844px;
}

.x76d897qj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.593 31.808a2.844 2.844 0 0 1 2.843-2.843h0m-2.843 0V36.5m-13.537-25h7.535l-7.535 11.374h7.535m3.063 12.191a2.84 2.84 0 0 1-2.471 1.435h0a2.844 2.844 0 0 1-2.844-2.844v-1.848a2.844 2.844 0 0 1 2.844-2.843h0a2.844 2.844 0 0 1 2.843 2.843v.924H17.34m-3.791-6.113v8.459c0 .785.636 1.422 1.422 1.422h.426m-3.341-7.536h2.986");
}

.yc09wh2nt {
  width: 5.687px;
  height: 7.535px;
  x: 30.257px;
  y: 15.339px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.844px;
  ry: 2.844px;
}

.ydqthzbbt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 42.5h-29c-2.2 0-4-1.8-4-4v-29c0-2.2 1.8-4 4-4h29c2.2 0 4 1.8 4 4v29c0 2.2-1.8 4-4 4");
}

</style>
