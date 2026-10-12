<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rm1sa67-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:milestone-sharp" /></template>
<style>
.rm1sa67-y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 17.5h3.5m11.5 0h3.5m-8.54-2.54l1.83 1.83l.71.71l-.71.71l-1.83 1.83l-.71.71l-.71-.71l-1.83-1.83l-.71-.71l.71-.71l1.83-1.83l.71-.71zM12 12V8.75m.75-5.5h5.5l-.4.63l-.95 1.49l-.4.63l.4.63l.95 1.49l.4.63H12v-5.5z");
}

</style>
