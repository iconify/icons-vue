<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gl6es8b0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:plug-puzzle-16-filled" /></template>
<style>
.gl6es8b0j {
  fill: currentColor;
  d: path("M2 11.193c0-.383.31-.693.692-.693H3a1.5 1.5 0 0 0 0-3h-.308A.693.693 0 0 1 2 6.808V5.5A2.5 2.5 0 0 1 4.5 3h1a.5.5 0 0 1 0 1h-1A1.5 1.5 0 0 0 3 5.5v1a2.5 2.5 0 0 1 0 5v1A1.5 1.5 0 0 0 4.5 14h5a1.5 1.5 0 0 0 1.5-1.5V9h-.5A2.5 2.5 0 0 1 8 6.5V5.3a1.3 1.3 0 0 1 1-1.264V2.5a.5.5 0 0 1 1 0V4h2V2.5a.5.5 0 0 1 1 0v1.536A1.3 1.3 0 0 1 14 5.3v1.2a2.5 2.5 0 0 1-2 2.45v3.55A2.5 2.5 0 0 1 9.5 15h-5A2.5 2.5 0 0 1 2 12.5z");
}

</style>
