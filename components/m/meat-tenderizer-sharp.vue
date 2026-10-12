<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xmylgdhnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:meat-tenderizer-sharp" /></template>
<style>
.xmylgdhnp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 4.75h6.5v10.5h-6.5l-2-1.75l2-1.75l-2-1.75l2-1.75l-2-1.75l2-1.75l-2-1.75Zm6.5 5.25h10");
}

</style>
