<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="ft5dv1b6b"><path class="khsbed5es"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:panel-right-expand-16-filled" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.khsbed5es {
  d: path("M9.707 8.5l.647.647a.5.5 0 0 1-.708.707l-1.5-1.5a.5.5 0 0 1 0-.707l1.5-1.5a.5.5 0 0 1 .708.707l-.647.646h1.791a.5.5 0 0 1 0 1h-1.79zM4 3a2 2 0 0 0-2 2V11a2 2 0 0 0 2 2h8a2 2 0 0 0 2-2V5a2 2 0 0 0-2-2H4zM7 12V4h5a1 1 0 0 1 1 1V11a1 1 0 0 1-1 1H7z");
  fill: currentColor;
}

</style>
