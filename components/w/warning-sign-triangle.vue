<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o8eav9b5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:warning-sign-triangle" /></template>
<style>
.o8eav9b5f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m15.033 8.268l3.446 5.986a3.5 3.5 0 0 1-3.033 5.246H8.554a3.5 3.5 0 0 1-3.033-5.246l3.446-5.986a3.5 3.5 0 0 1 6.066 0M12 9v4m0 3.5h.01");
}

</style>
