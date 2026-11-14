<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pderkkb9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:set-notation" /></template>
<style>
.pderkkb9a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 3.5c-2.5 0-2.5 2.5-2.5 5c0 2-1 3.5-2 3.5c1 0 2 1.5 2 3.5c0 2.5 0 5 2.5 5m6-17c2.5 0 2.5 2.5 2.5 5c0 2 1 3.5 2 3.5c-1 0-2 1.5-2 3.5c0 2.5 0 5-2.5 5M12 12h.01");
}

</style>
