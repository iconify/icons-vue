<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zyzpu7bmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:rating-star-empty" /></template>
<style>
.zyzpu7bmv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 3.5l2.939 4.955l5.621 1.264l-3.805 4.326l.535 5.736L12 17.5l-5.29 2.281l.535-5.736L3.44 9.719l5.621-1.264Z");
}

</style>
