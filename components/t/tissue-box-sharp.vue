<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lvvfq53pb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tissue-box-sharp" /></template>
<style>
.lvvfq53pb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 11.75h18.5v9.5H2.75zm0 3h18.5m-13-3c-1-2.75.5-5.5 3-6.25V3.143L14 2.75l-.385 2.308L16 6.25c-1.25 1.25-1.5 3.5-.75 5.5");
}

</style>
