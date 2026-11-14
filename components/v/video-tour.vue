<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="x70udq69y"/><path class="gvyohsz_i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:video-tour" /></template>
<style>
.gvyohsz_i {
  d: path("M15.5 6.5v-3H18v5M7 21v-3.5a2 2 0 0 1 4 0V21m4-6.5l6.5 3.5l-6.5 3.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x70udq69y {
  d: path("M12.231 21H3V11l9-7.5l9 7.5v3.569");
}

</style>
