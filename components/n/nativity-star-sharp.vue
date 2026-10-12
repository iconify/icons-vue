<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ggf1ueb_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:nativity-star-sharp" /></template>
<style>
.ggf1ueb_z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75q.69 5.06 5.75 5.75q-5.06.69-5.75 5.75q-.69-5.06-5.75-5.75q5.06-.69 5.75-5.75Zm0 11.5v7m2.75-15.5l1.5-1.5m-7 1.5l-1.5-1.5m7 7l1.5 1.5m-7-1.5l-1.5 1.5");
}

</style>
