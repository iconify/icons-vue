<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oa_9y3_-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mortar-pestle-stone-sharp" /></template>
<style>
.oa_9y3_-z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m14.01 10.89l3.98-6.78l.51-.86l.82.57l.86.61L21 5l-.51.86l-2.98 5.03l-.51.86h-3.5zM3 11.75h18c0 4-3.75 7-9 7s-9-3-9-7Zm5.5 9.5h7");
}

</style>
