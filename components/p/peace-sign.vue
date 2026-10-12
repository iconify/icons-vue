<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ebm1-bbff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:peace-sign" /></template>
<style>
.ebm1-bbff {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75a9.25 9.25 0 1 1 0 18.5a9.25 9.25 0 1 1 0-18.5m0 0v18.5M12 12l-6.54 6.54M12 12l6.54 6.54");
}

</style>
