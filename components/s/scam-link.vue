<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="is339abpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:scam-link" /></template>
<style>
.is339abpi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m10 14l4-4m-2.5-3L13 5.5a3.5 3.5 0 0 1 5.5 5.5L17 12.5M12.5 17L11 18.5A3.5 3.5 0 0 1 5.5 13L7 11.5m11 3.25v3.5M18 21h.01");
}

</style>
