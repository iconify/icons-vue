<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pin25vtky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pets-allowed" /></template>
<style>
.pin25vtky {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 11.5c3.5 0 6.5 4 6.5 6.75c0 2-1.75 3-3.5 2.5c-1.25-.35-2-.75-3-.75s-1.75.4-3 .75c-1.75.5-3.5-.5-3.5-2.5c0-2.75 3-6.75 6.5-6.75M7.25 5.25a1.5 2.25 0 1 0 3 0a1.5 2.25 0 1 0-3 0m6.5 0a1.5 2.25 0 1 0 3 0a1.5 2.25 0 1 0-3 0m-11 5a1.5 2 0 1 0 3 0a1.5 2 0 1 0-3 0m15.5 0a1.5 2 0 1 0 3 0a1.5 2 0 1 0-3 0");
}

</style>
