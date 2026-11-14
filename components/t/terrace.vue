<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i6au-nb3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:terrace" /></template>
<style>
.i6au-nb3i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 10.5h19v2h-19Zm0 11h19m-16.75-9h2.5v9h-2.5Zm6 0h2.5v9h-2.5Zm6 0h2.5v9h-2.5ZM9 7h6l-1 3.5h-4Zm3 0c0-2.5-1.5-4-3.5-4.5c0 2 1.5 4 3.5 4.5m0 0c0-2.5 1.5-4 3.5-4.5c0 2-1.5 4-3.5 4.5");
}

</style>
