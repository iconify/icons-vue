<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jmppb100p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:video-viewing" /></template>
<style>
.jmppb100p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3.5H15V13H2.5Zm14.968 7.639L15 10V6.5l6.5-3V13l-2.126-.981M14.25 18L18 14.5l3.75 3.5v3.75h-7.5Z");
}

</style>
