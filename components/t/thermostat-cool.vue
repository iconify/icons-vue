<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y55j_i_ae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:thermostat-cool" /></template>
<style>
.y55j_i_ae {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.551 19.782a9.5 9.5 0 1 1 10.898 0M12 2.5v2.75M12 8v8m3.464-6l-6.928 4m6.928 0l-6.928-4");
}

</style>
