<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eyu4wbenm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sparkles-multi" /></template>
<style>
.eyu4wbenm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 6.75c.25 4 2 6.25 5.5 6.75c-3.5.5-5.25 2.75-5.5 6.75c-.25-4-2-6.25-5.5-6.75c3.5-.5 5.25-2.75 5.5-6.75Zm9-4.25c.25 1.75 1 2.75 2.75 3c-1.75.25-2.5 1.25-2.75 3c-.25-1.75-1-2.75-2.75-3c1.75-.25 2.5-1.25 2.75-3ZM19 16v5m-2.5-2.5h5");
}

</style>
