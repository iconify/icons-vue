<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hnhuhuc2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-color-accent-20-filled" /></template>
<style>
.hnhuhuc2s {
  fill: currentColor;
  d: path("M3.5 13.125c0-.345.243-.625.542-.625h11.916c.3 0 .542.28.542.625v3.75c0 .345-.242.625-.542.625H4.042c-.3 0-.542-.28-.542-.625z");
}

</style>
