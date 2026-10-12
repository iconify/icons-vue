<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="wtgqq3bwn"/><path class="qzos8tbtf"/><circle class="z_9qmublw"/><circle class="nz_nwmb4o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mobile-home-sharp" /></template>
<style>
.nz_nwmb4o {
  cx: 13.5px;
  cy: 19.25px;
  r: 2px;
}

.qzos8tbtf {
  d: path("M14.5 17.25v-5h3v5M7 10.5h4v2.75H7Z");
}

.wtgqq3bwn {
  d: path("M3.75 16.25V9l.92-.39l6.41-2.72l.92-.39l.94.35l7.37 2.8l.94.35v8.25H3.75zm0-1h-1");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z_9qmublw {
  cx: 7px;
  cy: 19.25px;
  r: 2px;
}

</style>
