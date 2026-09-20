<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="j7kll47bp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:speaker-high-bold" /></template>
<style>
.j7kll47bp {
  fill: currentColor;
  d: path("M157.27 21.22a12 12 0 0 0-12.64 1.31L75.88 76H32a20 20 0 0 0-20 20v64a20 20 0 0 0 20 20h43.88l68.75 53.47A12 12 0 0 0 164 224V32a12 12 0 0 0-6.73-10.78M36 100h32v56H36Zm104 99.46l-48-37.33V93.87l48-37.33ZM212 128a44 44 0 0 1-11 29.11a12 12 0 1 1-18-15.88a20 20 0 0 0 0-26.43a12 12 0 0 1 18-15.86A43.94 43.94 0 0 1 212 128m40 0a83.87 83.87 0 0 1-21.39 56a12 12 0 0 1-17.89-16a60 60 0 0 0 0-80a12 12 0 1 1 17.88-16a83.87 83.87 0 0 1 21.4 56");
}

</style>
