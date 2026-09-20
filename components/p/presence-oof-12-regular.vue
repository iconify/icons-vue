<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="d_20oz_bf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:presence-oof-12-regular" /></template>
<style>
.d_20oz_bf {
  fill: currentColor;
  d: path("M6.281 4.528a.75.75 0 0 0-1.06-1.06L3.218 5.47a.75.75 0 0 0 0 1.06l2.003 2.003a.75.75 0 0 0 1.06-1.061L5.56 6.75h2.69a.75.75 0 1 0 0-1.5H5.56zM6 0a6 6 0 1 0 0 12A6 6 0 0 0 6 0M1.5 6a4.5 4.5 0 1 1 9 0a4.5 4.5 0 0 1-9 0");
}

</style>
