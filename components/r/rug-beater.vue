<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lhbunzbnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:rug-beater" /></template>
<style>
.lhbunzbnm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 9a6 6.5 0 1 0 12 0A6 6.5 0 1 0 6 9Zm3.525 5.475l-5.657 5.657M12.53 4.045l7.425 7.425M9.879 5.636l8.485 8.485M8.288 8.288l7.424 7.424");
}

</style>
