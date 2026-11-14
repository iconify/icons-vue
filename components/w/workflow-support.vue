<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mdc2l1-1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:workflow-support" /></template>
<style>
.mdc2l1-1h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3H9v5H2.5ZM15 3h6.5v5H15ZM2.5 15H9v5H2.5ZM9 5.5h6M5.75 8v7m8.75 3a3.25 3.25 0 0 1 6.5 0m-7.5 0h2v3.5h-2Zm6.5 0h2v3.5h-2Z");
}

</style>
