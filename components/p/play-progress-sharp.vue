<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bs7l5kcfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:play-progress-sharp" /></template>
<style>
.bs7l5kcfr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8.88 5.05l9.24 5.65l2.13 1.3l-2.13 1.3l-9.24 5.65l-2.13 1.3V3.75z");
}

</style>
