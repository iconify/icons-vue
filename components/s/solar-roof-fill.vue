<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="r2hjrzjqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:solar-roof-fill" /></template>
<style>
.r2hjrzjqj {
  fill: currentColor;
  d: path("m247.16 124.42l-40-80A8 8 0 0 0 200 40H56a8 8 0 0 0-7.16 4.42l-40 80A8.1 8.1 0 0 0 8 128v56a16 16 0 0 0 16 16h208a16 16 0 0 0 16-16v-56a8.1 8.1 0 0 0-.84-3.58M99.06 56l12 24H80.94l-12-24Zm48 0l12 24h-30.12l-12-24Zm-46.12 64l-12-24h30.12l12 24Zm48 0l-12-24h30.12l12 24Zm48 0l-12-24h30.12l12 24Zm10.12-40h-30.12l-12-24h30.12ZM104 184v-48h128v48Z");
}

</style>
