<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="qwky70bif"/><path class="kj_fl4bwe"/><rect class="evsvr_51t"/><path class="tx51rfb5o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:quote" /></template>
<style>
.evsvr_51t {
  width: 6.75px;
  height: 7.75px;
  x: 13.5px;
  y: 11px;
  rx: 1.75px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kj_fl4bwe {
  d: path("M4.75 11q.375-4.125 4.5-5.25");
}

.qwky70bif {
  width: 6.75px;
  height: 7.75px;
  x: 3.5px;
  y: 11px;
  rx: 1.75px;
}

.tx51rfb5o {
  d: path("M14.75 11q.375-4.125 4.5-5.25");
}

</style>
