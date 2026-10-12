<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="f_xhfg_oj"/><path class="ibvhz7ctv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:reel-play-sharp" /></template>
<style>
.f_xhfg_oj {
  d: path("M2.75 2.75h18.5v18.5H2.75zm0 5.5h18.5m-13-5.5l2.5 5.5M14 2.75l2.5 5.5");
}

.ibvhz7ctv {
  d: path("M10.25 11.6v5.3l-.029 1.394l1.179-.744l4.1-2.65l1.129-.65l-1.129-.65l-4.1-2.65l-1.179-.744z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
