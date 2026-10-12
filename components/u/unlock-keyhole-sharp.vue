<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hrs9o4gen"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:unlock-keyhole-sharp" /></template>
<style>
.hrs9o4gen {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 10.75h14.5v10.5H4.75zm3 0V7.5a4.25 4.25 0 0 1 8.2-1.55M12 14.75v2.5");
}

</style>
