<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v8t1m6bbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mobility-scooter" /></template>
<style>
.v8t1m6bbi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 18a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Zm12 0a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Zm-6.5 0h6.5m3.75-3l-3-8.5h-3m-10 2h7v3h-7Zm.5-4v4");
}

</style>
