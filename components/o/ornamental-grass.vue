<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fl-x5ubks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ornamental-grass" /></template>
<style>
.fl-x5ubks {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 21.5Q9 13 3 10m9 11.5Q10.5 10 8 3m4 18.5Q13.5 10 16 3m-4 18.5Q15 13 21 10M7 21.5h10");
}

</style>
