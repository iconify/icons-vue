<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o9x_xx4zx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:megaphone-off-sharp" /></template>
<style>
.o9x_xx4zx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 10V8.5h4.5l7.45-4.4l1.49-.86l.01 1.72v14.08l-.01 1.72l-1.49-.86l-7.45-4.4h-4.5V14Zm4.5 5.5l1.25 4.75m10.75-10.5v4.5");
}

</style>
