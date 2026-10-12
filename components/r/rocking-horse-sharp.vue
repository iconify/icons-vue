<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wdh3d3b9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rocking-horse-sharp" /></template>
<style>
.wdh3d3b9c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.4 9.5H14l.26-.86l.98-3.28l.26-.86l.76-.48l.48-.29l.76-.48l.64.64l1.47 1.47l.64.64l-.5.63l-.5.62l-.75-.12l-.75-.13l-.1.89l-.55 4.72l-.1.89H5.5v-4zm-.9 1L3.25 13m4.25.5L6.25 19M15 13.5l1.25 5.5m-13.5-1c5.5 3 13 3 18.5 0");
}

</style>
