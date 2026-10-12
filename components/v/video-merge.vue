<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="no_w0erxd"/><rect class="vbluk1h1e"/><path class="uuoba0n6h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:video-merge" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.no_w0erxd {
  d: path("M2.75 6h2.5a3 3 0 0 1 2.4 1.2L11 12m-8.25 6h2.5a3 3 0 0 0 2.4-1.2L11 12h2");
}

.uuoba0n6h {
  d: path("m16.49 10.35l1.77 1.3q.49.35 0 .7l-1.77 1.3Q16 14 16 13.4v-2.8q0-.6.49-.25");
}

.vbluk1h1e {
  width: 8.25px;
  height: 10.5px;
  x: 13px;
  y: 6.75px;
  rx: 2px;
}

</style>
