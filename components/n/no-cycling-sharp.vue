<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nkrj57uuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:no-cycling-sharp" /></template>
<style>
.nkrj57uuh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 16a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm14.5-3.5a3.5 3.5 0 0 1 3.17 4.98m-4.71 1.66l-1.073-.527l-.527-1.073m1.66-4.71l.703-.329l.777-.001M6.5 16l.5-5.75m-2 0h2.07M7 12.5l1.86-.45m5.12-1.25l3.27-.8m.14 4.2L17 8m-1.5 0h3M3.75 3.75l16.5 16.5");
}

</style>
