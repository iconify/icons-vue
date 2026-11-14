<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="im5qf78ak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mortgage-rate" /></template>
<style>
.im5qf78ak {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 5.25a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm7.5 7.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM3 15L15 3m-.25 14.25l3.5-2.75l3.5 2.75m-7 0h7m-5.5 0v4.25m4-4.25v4.25m-5.5 0h7");
}

</style>
