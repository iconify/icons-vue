<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dr9zacc0w"/><path class="tivyg7boa"/><path class="n_vd-j_xf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:neon-open" /></template>
<style>
.dr9zacc0w {
  d: path("M2.5 9h19v12.5h-19ZM7 9l5-3.75L17 9m-5-3.75h.01");
}

.n_vd-j_xf {
  d: path("M12 2v1M4 4.5l1.25 1.25M20 4.5l-1.25 1.25");
}

.tivyg7boa {
  fill: currentColor;
  d: path("M13 10.75L8.5 16h3l-1 4l5-5.75h-3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
