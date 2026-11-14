<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iq68olbze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:password-dots" /></template>
<style>
.iq68olbze {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 8v5m-2-3.75l4 2.5m-4 0l4-2.5M12 8v5m-2-3.75l4 2.5m-4 0l4-2.5M19.5 8v5m-2-3.75l4 2.5m-4 0l4-2.5M2.5 17h19");
}

</style>
