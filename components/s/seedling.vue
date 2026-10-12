<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zszcn1bot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:seedling" /></template>
<style>
.zszcn1bot {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 21.25c1.25-3 4.75-4.5 8.75-4.5s7.5 1.5 8.75 4.5Zm8.75-4.5v-5.5m0 0C11.75 8.5 10 7 7 7c.25 2.75 2 4.25 5 4.25m0 0C12.25 8.5 14 7 17 7c-.25 2.75-2 4.25-5 4.25");
}

</style>
