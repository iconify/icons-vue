<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iuv1fkuvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pet-grooming-appointment" /></template>
<style>
.iuv1fkuvt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 4.5h17V21h-17Zm4.5-2v4m8-4v4m-12.5 3h17m-14 0v2.25M9.25 9.5v2.25M12 9.5v2.25m2.75-2.25v2.25M17.5 9.5v2.25M8 16.25h.01m3.99 0h.01m3.99 0h.01");
}

</style>
