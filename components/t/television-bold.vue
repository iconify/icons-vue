<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="w6lyttbwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:television-bold" /></template>
<style>
.w6lyttbwe {
  fill: currentColor;
  d: path("M216 60h-59l27.52-27.52a12 12 0 0 0-17-17L128 55L88.49 15.51a12 12 0 0 0-17 17L99 60H40a20 20 0 0 0-20 20v120a20 20 0 0 0 20 20h176a20 20 0 0 0 20-20V80a20 20 0 0 0-20-20M44 84h84v112H44Zm168 112h-60V84h60Zm-44-80a16 16 0 1 1 16 16a16 16 0 0 1-16-16m32 48a16 16 0 1 1-16-16a16 16 0 0 1 16 16");
}

</style>
