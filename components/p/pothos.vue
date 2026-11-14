<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vtyd85b5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pothos" /></template>
<style>
.vtyd85b5t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5c-1.25 5.5 1.25 12.5 0 19M11.5 6H8.25M12 12h3.75m-3.5 6h-4m0-12C9.75 5 9.5 2.5 7 2.75C5.25 3 4 4.75 2.75 6C4 7.25 5.25 9 7 9.25C9.5 9.5 9.75 7 8.25 6Zm7.5 6c-1.5-1-1.25-3.5 1.25-3.25c1.75.25 3 2 4.25 3.25c-1.25 1.25-2.5 3-4.25 3.25c-2.5.25-2.75-2.25-1.25-3.25Zm-7.5 6c1.5-1 1.25-3.5-1.25-3.25c-1.75.25-3 2-4.25 3.25C4 19.25 5.25 21 7 21.25C9.5 21.5 9.75 19 8.25 18Z");
}

</style>
