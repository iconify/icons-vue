<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="giriwn1vk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:role-definition" /></template>
<style>
.giriwn1vk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.197 4.211a3.5 3.5 0 0 1 1.834 1.539m.258 2.947a3.5 3.5 0 0 1-1.539 1.834m-2.947.258A3.5 3.5 0 0 1 5.969 9.25m-.258-2.947A3.5 3.5 0 0 1 7.25 4.469M3 20.5c0-2 .5-3.5 1.75-4.5m2.5-1.5c1-.25 2.5-.25 3.5 0m2.5 1.5C14.5 17 15 18.5 15 20.5m3.669-14.47l2.819 1.026l-2.394 6.578L17 15l-.725-2.392Zm-2.394 6.578l2.819 1.026");
}

</style>
