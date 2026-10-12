<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="rbck-mbrp"/><rect class="ohk97gbpm"/><path class="rsrswbbvp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:party-whistle" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ohk97gbpm {
  width: 8px;
  height: 2.5px;
  x: 8px;
  y: 10.75px;
  rx: 0.6px;
}

.rbck-mbrp {
  width: 4.5px;
  height: 3.5px;
  x: 2.75px;
  y: 10.25px;
  rx: 1.25px;
}

.rsrswbbvp {
  d: path("M16 12h2.25a3 3 0 0 1 0 6h-1.5a1.5 1.5 0 0 1 0-3h.75M9 6.25l1-1.5m3 1v-2m3.5 2.5l1-1.25");
}

</style>
