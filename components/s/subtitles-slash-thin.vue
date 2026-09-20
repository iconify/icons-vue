<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="xu4r6xoeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:subtitles-slash-thin" /></template>
<style>
.xu4r6xoeq {
  fill: currentColor;
  d: path("M52 136a4 4 0 0 1 4-4h16a4 4 0 0 1 0 8H56a4 4 0 0 1-4-4m159 77.31a4 4 0 1 1-5.92 5.38L191.69 204H32a12 12 0 0 1-12-12V64a12 12 0 0 1 12-12h21.5L45 42.69a4 4 0 0 1 6-5.38ZM184.41 196l-21.82-24H56a4 4 0 0 1 0-8h99.32l-21.82-24H104a4 4 0 0 1 0-8h22.23L60.78 60H32a4 4 0 0 0-4 4v128a4 4 0 0 0 4 4ZM200 140a4 4 0 0 0 0-8h-21.48a4 4 0 1 0 0 8Zm24-88H105.79a4 4 0 0 0 0 8H224a4 4 0 0 1 4 4v130.83a4 4 0 1 0 8 0V64a12 12 0 0 0-12-12");
}

</style>
