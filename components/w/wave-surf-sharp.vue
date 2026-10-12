<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s4niwbbce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:wave-surf-sharp" /></template>
<style>
.s4niwbbce {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 20.75C3.5 12 8.5 5 15 5c3.5 0 6.25 2 6.25 5c0 2.25-1.75 3.75-3.75 3.75c-1.75 0-3-1.25-3-2.75V9.583l1.25-.833C11 9 8.5 14.5 8.5 20.75Zm8.05-1.29l9.4-3.42");
}

</style>
