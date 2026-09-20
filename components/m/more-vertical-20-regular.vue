<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tgvb_lmst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:more-vertical-20-regular" /></template>
<style>
.tgvb_lmst {
  fill: currentColor;
  d: path("M10 6a1.25 1.25 0 1 1 0-2.5A1.25 1.25 0 0 1 10 6m0 5.25a1.25 1.25 0 1 1 0-2.5a1.25 1.25 0 0 1 0 2.5m-1.25 4a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 0 0-2.5 0");
}

</style>
