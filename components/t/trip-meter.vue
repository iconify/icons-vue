<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uig--_1oe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:trip-meter" /></template>
<style>
.uig--_1oe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 5H7v6.5H2.5Zm7.25 0h4.5v6.5h-4.5ZM17 5h4.5v6.5H17ZM7 17h9.5m-2.25-2.25L16.5 17l-2.25 2.25");
}

</style>
