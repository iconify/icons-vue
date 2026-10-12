<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="diknjcc5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:manta-ray-sharp" /></template>
<style>
.diknjcc5k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 6.25c-3 0-6 2-9.25 6.5C6 14 9 15.25 11 17.5h2c2-2.25 5-3.5 8.25-4.75C18 8.25 15 6.25 12 6.25Zm-1.75.25L9.5 3.75m4.25 2.75l.75-2.75M10 10.5h4m-2 7v3.75");
}

</style>
