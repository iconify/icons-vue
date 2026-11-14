<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fa_nbjbrc"/><path class="qnvxqebrk"/><path class="u__znebfc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pedestrian-detour" /></template>
<style>
.fa_nbjbrc {
  d: path("M12 2.25L21.75 12L12 21.75L2.25 12Zm-1.5 14v-8.5");
}

.qnvxqebrk {
  d: path("M10.5 14q0-4 4-4h.75");
}

.u__znebfc {
  d: path("m13.25 8l2 2l-2 2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
