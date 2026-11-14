<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cjypv688z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:wellness-program" /></template>
<style>
.cjypv688z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 4.5C14.75 7 14.75 12 12 15c-2.75-3-2.75-8 0-10.5Zm0 13c-5 0-8.5-3-9-8c3 .25 5.5 1.5 6.75 3.25M12 17.5c5 0 8.5-3 9-8c-3 .25-5.5 1.5-6.75 3.25");
}

</style>
