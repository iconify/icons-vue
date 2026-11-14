<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="un0hh0-9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:test-flaky" /></template>
<style>
.un0hh0-9x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.904 16.854l4.95-4.95a1 1 0 0 1 1.414 0l2.828 2.828a1 1 0 0 1 0 1.414l-4.95 4.95a1 1 0 0 1-1.414 0l-2.828-2.828a1 1 0 0 1 0-1.414Zm9-9l4.95-4.95a1 1 0 0 1 1.414 0l2.828 2.828a1 1 0 0 1 0 1.414l-4.95 4.95a1 1 0 0 1-1.414 0l-2.828-2.828a1 1 0 0 1 0-1.414ZM16 16l2 2M8 8L6 6");
}

</style>
