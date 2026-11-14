<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="srpsm5kxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:shelf-pusher" /></template>
<style>
.srpsm5kxm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 16.5h19v3h-19Zm7.5-9h8.5v9H10Zm-3.5 0v9m0-4.5H10M3 3.5h11M11.5 2L14 3.5L11.5 5");
}

</style>
