<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yvk3xmbbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sign-holder-counter" /></template>
<style>
.yvk3xmbbl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 3h10l-1.5 14h-10ZM3.5 17h10l7 3.5h-10Zm10 0L15 3M6.5 7h6M6 10.5h5.5m-6 3.5h5");
}

</style>
