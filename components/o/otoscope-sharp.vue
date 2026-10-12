<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q8keavtxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:otoscope-sharp" /></template>
<style>
.q8keavtxx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 6.75H6.5v3.5H2.75zm3.75-1h8v5.5h-8zm8.73.66l5.29 1.18l.73.16v1.5l-.73.16l-5.29 1.18l-.73.16v-4.5zM8.5 11.25h4v10h-4zm0 3.5h4m-4 3h4");
}

</style>
