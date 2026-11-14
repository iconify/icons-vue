<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-7p_onkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tooth-milk" /></template>
<style>
.i-7p_onkx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.962 20.5H5.5L4 2.5h13l-.806 9.666M4.5 8.5h12m0 6.5c-1.25 0-1.75 1-1.75 2.25s.75 1.75 1 2.75l.5 1.5l1.5-2l1.5 2l.5-1.5c.25-1 1-1.5 1-2.75S20.25 15 19 15c-.75 0-.75.5-1.25.5s-.5-.5-1.25-.5Z");
}

</style>
