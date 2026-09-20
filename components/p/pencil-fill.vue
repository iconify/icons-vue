<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="pehw7nhcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:pencil-fill" /></template>
<style>
.pehw7nhcy {
  fill: currentColor;
  d: path("m227.31 73.37l-44.68-44.69a16 16 0 0 0-22.63 0L36.69 152A15.86 15.86 0 0 0 32 163.31V208a16 16 0 0 0 16 16h44.69a15.86 15.86 0 0 0 11.31-4.69L227.31 96a16 16 0 0 0 0-22.63M51.31 160l90.35-90.35l16.68 16.69L68 176.68ZM48 179.31L76.69 208H48Zm48 25.38L79.31 188l90.35-90.35l16.68 16.69Z");
}

</style>
