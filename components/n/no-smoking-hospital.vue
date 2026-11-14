<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-fx25blh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:no-smoking-hospital" /></template>
<style>
.p-fx25blh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.3 17.25H2.5v-3.5h7.3m7.9 0h3.8v3.5h-.3m-14.7-3.5v3.5m-2-3.5v3.5m16-5.25c-1.25-1.25.75-2.5-.25-4c-.75-1.25.25-2.25 1-3M3.5 3.5l17 17");
}

</style>
