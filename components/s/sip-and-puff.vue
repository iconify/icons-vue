<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e6-t3vbhj"/><rect class="uvb1rhbai"/><path class="gn5_7fb7i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sip-and-puff" /></template>
<style>
.e6-t3vbhj {
  d: path("M4.15 14.75v-2.12c-.88-.88-1.4-2.16-1.4-3.68c0-3.4 2.28-6.2 5.2-6.2c2.16 0 3.52 1.4 3.8 3.4l1.12 2.08q.2.52-.32.52h-.6v2q0 1.6-1.4 1.6h-1v2.4Zm8.8-5h3.3a2 2 0 0 1 2 2v2");
}

.gn5_7fb7i {
  d: path("M15.75 17.5h3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uvb1rhbai {
  width: 7.5px;
  height: 7.5px;
  x: 13.75px;
  y: 13.75px;
  rx: 2px;
}

</style>
