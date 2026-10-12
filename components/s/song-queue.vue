<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="yka_slb0u"/><path class="glu0wjbqw"/><circle class="kb5j5hb3j"/><path class="pd2s03bbm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:song-queue" /></template>
<style>
.glu0wjbqw {
  d: path("M5.5 6h10.25A2.25 2.25 0 0 1 18 8.25v9.5M8 3.25h10.25a2 2 0 0 1 2 2V15");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kb5j5hb3j {
  cx: 7.75px;
  cy: 16.25px;
  r: 1.5px;
}

.pd2s03bbm {
  d: path("M9.25 16.25v-4.5l2 .75");
}

.yka_slb0u {
  width: 13px;
  height: 11.75px;
  x: 2.75px;
  y: 8.75px;
  rx: 2px;
}

</style>
