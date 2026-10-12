<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="objs63yii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:space-shuttle-sharp" /></template>
<style>
.objs63yii {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.47 3.63l1.31 2.49l.47.88v3.5l.73.68l5.04 4.64l.73.68v2.25H3.25V16.5l.73-.68l5.04-4.64l.73-.68V7l.47-.88l1.31-2.49l.47-.88zM12 11.5v5m-1.5 2.25H14l.1.49l.3 1.52l.1.49h-5l.1-.49l.3-1.52l.1-.49z");
}

</style>
