<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ffqz4qpwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:schema-tree" /></template>
<style>
.ffqz4qpwv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 3.5h6v4h-6Zm8.5 6h8.5v4H12Zm0 7h8.5v4H12Zm-5.5-9v11m0-7H12m-5.5 7H12");
}

</style>
