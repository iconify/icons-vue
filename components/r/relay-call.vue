<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fg6sdznww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:relay-call" /></template>
<style>
.fg6sdznww {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.731 18.016C7.157 16.453 3 11.285 3 5.25C3 4 4 3 5.25 3H7.5l1.75 4L7.5 8.5c1 2 3.5 4.5 5.5 5.5l1.5-1.75l1.167.511M15.5 16.5a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v2.75a1 1 0 0 1-1 1h-2l-2 1.5v-1.5a1 1 0 0 1-1-1Z");
}

</style>
