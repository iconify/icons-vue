<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<g class="ft5dv1b6b"><path class="irkn49b_k"/><path class="yjqdkbxnv"/><path class="ldgze-b-i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:more-24-filled" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.irkn49b_k {
  d: path("M8.334 12a2 2 0 1 1-4 0a2 2 0 0 1 4 0z");
  fill: currentColor;
}

.ldgze-b-i {
  d: path("M18.334 14a2 2 0 1 0 0-4a2 2 0 0 0 0 4z");
  fill: currentColor;
}

.yjqdkbxnv {
  d: path("M14.334 12a2 2 0 1 1-4 0a2 2 0 0 1 4 0z");
  fill: currentColor;
}

</style>
