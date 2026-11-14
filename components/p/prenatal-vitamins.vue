<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jj4vsjb2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:prenatal-vitamins" /></template>
<style>
.jj4vsjb2y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.387 19.583L10.25 21.5H5V17c-.75-1.5-1.25-4-1-6c.25-1.5.75-2.5 1.5-2.5h3c1 0 1.5.5 1.75 1.5l.25 1c2.284.685 3.734 2.206 3.776 3.989m-3.085 3.048A5 5 0 0 1 10.5 18l-.056.785M5.25 4.75a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm8.684 14.487l5.303-5.303l2.829 2.829l-5.303 5.303Zm2.652-2.651l2.828 2.828");
}

</style>
