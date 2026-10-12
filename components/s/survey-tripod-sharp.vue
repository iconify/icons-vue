<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="udaywsbvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:survey-tripod-sharp" /></template>
<style>
.udaywsbvo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 9.5L4.5 21.25M12 9.5l7.5 11.75M12 9.5v11.75M8 7h8v2.5H8zm.75 0a3.25 3.25 0 0 1 6.5 0ZM12 3.75v-1");
}

</style>
