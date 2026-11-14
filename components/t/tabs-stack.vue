<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pk283zbqn"/><path class="l77nipb4t"/><path class="enahejbnu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tabs-stack" /></template>
<style>
.enahejbnu {
  d: path("m9 5.75l1.25-3.25H14L15.25 5H21v10h-3.25");
}

.l77nipb4t {
  d: path("m5.75 9l1.5-3.25H11l1.25 2.5h5.5v10H14.5");
}

.pk283zbqn {
  d: path("M2.5 21.5v-10L3.75 9h4L9 11.5h5.5v10Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
