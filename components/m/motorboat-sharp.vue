<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="snzyiex9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:motorboat-sharp" /></template>
<style>
.snzyiex9x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 13.75v-6h7.5l.3.69l2.4 5.37l.3.69H7.75zm2-3h1.5m2 0h1.5m-8.5 3.75h15L20 18.25l-.355 1.004l-1.065-.004H7.67l-1.065.004l-.355-1.004Zm-2.75-4h1.75v4h-2.5v-4zm.5 4V18");
}

</style>
