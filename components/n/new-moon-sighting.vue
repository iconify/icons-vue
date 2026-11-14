<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pgdq3cc5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:new-moon-sighting" /></template>
<style>
.pgdq3cc5w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3a9 9 0 0 0 0 18a11 11 0 0 1 0-18Zm1.612 12.249l6.797-3.17l1.479 3.172l-6.797 3.17ZM17.75 16.5l-2 5m2-5l2.25 5");
}

</style>
