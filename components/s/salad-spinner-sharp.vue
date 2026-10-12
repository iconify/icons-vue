<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jma15ofrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:salad-spinner-sharp" /></template>
<style>
.jma15ofrs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 10.25v-5h4.75V7m-13.5 3.25h17.5v3.5a7.5 7.5 0 0 1-7.5 7.5h-2.5a7.5 7.5 0 0 1-7.5-7.5Zm0 3h17.5");
}

</style>
