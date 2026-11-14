<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nhomhtbff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:platelets" /></template>
<style>
.nhomhtbff {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 7.5c0-2 2-3 4-2.5c2-.75 4 .25 3.5 2.5c.5 2-1.5 3-3.5 2.5c-2 .75-4-.25-4-2.5m8.75 5c-.25-2 1.75-3.25 3.5-2.75c2-.75 3.75.5 3.5 2.5c.5 2-1.25 3.5-3.25 3c-2 .5-3.75-.75-3.75-2.75M4 17.5c0-2 2-3.25 4-2.75c2-.75 4 .5 3.75 2.5c.25 2.25-1.75 3.5-3.75 3c-2 .75-4-.75-4-2.75");
}

</style>
