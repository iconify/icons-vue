<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="sg0tgxb7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:speaker-simple-x-fill" /></template>
<style>
.sg0tgxb7f {
  fill: currentColor;
  d: path("M163.52 24.81a8 8 0 0 0-8.43.88L85.25 80H40a16 16 0 0 0-16 16v64a16 16 0 0 0 16 16h45.25l69.84 54.31A7.94 7.94 0 0 0 160 232a8 8 0 0 0 8-8V32a8 8 0 0 0-4.48-7.19M235.31 128l18.35-18.34a8 8 0 0 0-11.32-11.32L224 116.69l-18.34-18.35a8 8 0 0 0-11.32 11.32L212.69 128l-18.35 18.34a8 8 0 0 0 11.32 11.32L224 139.31l18.34 18.35a8 8 0 0 0 11.32-11.32Z");
}

</style>
