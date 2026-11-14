<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o_vkbdc0o"/><path class="zxew3ilom"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:photo-id-search" /></template>
<style>
.o_vkbdc0o {
  d: path("M13.1 20H2.5V3h19v11.4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zxew3ilom {
  d: path("M6.25 8.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm-1 6.75a2.5 2.5 0 0 1 5 0M13.5 9h5m-3.25 8.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm4 1.75L21 21");
}

</style>
