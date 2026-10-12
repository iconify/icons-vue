<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q3qi4mb-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:voice-control-sharp" /></template>
<style>
.q3qi4mb-g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 21.25V18c-1.75-1.5-2.75-3.75-2.75-6.5A7.25 7.25 0 0 1 10 4.25h.25a5.5 5.5 0 0 1 5.5 5.5l1.5 2.75l-1.5.75v4H12.5v4Zm13.75-12.5a4.75 4.75 0 0 1 0 7.5");
}

</style>
