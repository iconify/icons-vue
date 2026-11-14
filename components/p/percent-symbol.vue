<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gjt1gibwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:percent-symbol" /></template>
<style>
.gjt1gibwd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 7a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Zm10 10a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0ZM18.5 4.5l-13 15");
}

</style>
