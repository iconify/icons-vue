<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xk87rubzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:spine-sharp" /></template>
<style>
.xk87rubzr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.42 3.11l4.48-.31l1-.07l.07 1l.04.49l.07 1l-1 .07l-4.48.31l-1 .07l-.07-1l-.04-.49l-.07-1zm1.79 5.17l4.49-.16l1-.03l.04 1l.01.5l.04 1l-1 .03l-4.49.16l-1 .03l-.04-1l-.01-.5l-.04-1zm.09 4.94l4.49.16l1 .03l-.04 1l-.01.5l-.04 1l-1-.03l-4.49-.16l-1-.03l.04-1l.01-.5l.04-1zM6.6 18.4l4.48.31l1 .07l-.07 1l-.04.49l-.07 1l-1-.07l-4.48-.31l-1-.07l.07-1l.04-.49l.07-1zm8.65-15.65c1.5 2.75 2 5.75 2 9.25s-.5 6.5-2 9.25");
}

</style>
