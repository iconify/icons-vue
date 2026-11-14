<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a2dkm2eur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:snowflake-simple" /></template>
<style>
.a2dkm2eur {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5v19m8.227-14.25l-16.454 9.5m16.454 0L3.773 7.25m5.977-3L12 6.5l2.25-2.25m3.337 1.926l-.824 3.074l3.074.824m0 3.852l-3.074.824l.824 3.074M14.25 19.75L12 17.5l-2.25 2.25m-3.337-1.926l.824-3.074l-3.074-.824m0-3.852l3.074-.824l-.824-3.074");
}

</style>
