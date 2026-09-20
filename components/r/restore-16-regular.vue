<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="ft5dv1b6b"><path class="a59fy4w7n"/><path class="sxfkq2c6g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:restore-16-regular" /></template>
<style>
.a59fy4w7n {
  d: path("M5.085 4A1.5 1.5 0 0 1 6.5 3H10a3 3 0 0 1 3 3v3.5a1.5 1.5 0 0 1-1 1.415V6a2 2 0 0 0-2-2H5.085z");
  fill: currentColor;
}

.ft5dv1b6b {
  fill: none;
}

.sxfkq2c6g {
  d: path("M4.5 5h5A1.5 1.5 0 0 1 11 6.5v5A1.5 1.5 0 0 1 9.5 13h-5A1.5 1.5 0 0 1 3 11.5v-5A1.5 1.5 0 0 1 4.5 5zm0 1a.5.5 0 0 0-.5.5v5a.5.5 0 0 0 .5.5h5a.5.5 0 0 0 .5-.5v-5a.5.5 0 0 0-.5-.5h-5z");
  fill: currentColor;
}

</style>
