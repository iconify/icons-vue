<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hk6knwgql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:octagram-sharp" /></template>
<style>
.hk6knwgql {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.29 3.4l1.79 2.47l.29.4l.5-.08l3-.48l.49-.07l-.07.49l-.48 3l-.08.5l.4.29l2.47 1.79l.4.29l-.4.29l-2.47 1.79l-.4.29l.08.5l.48 3l.07.49l-.49-.07l-3-.48l-.5-.08l-.29.4l-1.79 2.47l-.29.4l-.29-.4l-1.79-2.47l-.29-.4l-.5.08l-3 .48l-.49.07l.07-.49l.48-3l.08-.5l-.4-.29l-2.47-1.79L3 12l.4-.29l2.47-1.79l.4-.29l-.08-.5l-.48-3l-.07-.49l.49.07l3 .48l.5.08l.29-.4l1.79-2.47L12 3z");
}

</style>
