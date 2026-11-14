<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p_yyel2um"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sedation-dental" /></template>
<style>
.p_yyel2um {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.244 14.972L12 13.75c-.25-1-2.75-1-3 0l-.75 3.75C8 19 6.25 19 6 17.5L5.25 13c-.5-2.25-1.75-3.5-1.75-6c0-2.75 1-4.5 3.5-4.5c1.75 0 2.25 1 3.5 1s1.75-1 3.5-1c2.5 0 3.5 1.75 3.5 4.5c0 1.984-.787 3.18-1.362 4.714M19.5 14.5a3.75 3.75 0 1 0 2 5a3 3 0 0 1-2-5Z");
}

</style>
