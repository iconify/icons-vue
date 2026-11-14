<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wlrj-mbve"/><path class="h2p_xr55b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:nose-piercing" /></template>
<style>
.h2p_xr55b {
  d: path("M11.5 18c-2 0-2-3.5.5-3.5m1.75 5.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wlrj-mbve {
  d: path("M7 2.5c1.5 5 6 8.5 10 12c1.5 1.5.5 3.5-1.5 3.5h-4");
}

</style>
