<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="ft5dv1b6b"><path class="d6wuz7bcc"/><path class="xks-ddb1e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:mic-on-20-regular" /></template>
<style>
.d6wuz7bcc {
  d: path("M10 13a3 3 0 0 0 3-3V5a3 3 0 1 0-6 0v5a3 3 0 0 0 3 3zm0-1a2 2 0 0 1-2-2V5a2 2 0 1 1 4 0v5a2 2 0 0 1-2 2z");
  fill: currentColor;
}

.ft5dv1b6b {
  fill: none;
}

.xks-ddb1e {
  d: path("M5 9.5a.5.5 0 0 1 .5.5a4.5 4.5 0 1 0 9 0a.5.5 0 0 1 1 0a5.5 5.5 0 0 1-5 5.478V17.5a.5.5 0 0 1-1 0v-2.022A5.5 5.5 0 0 1 4.5 10a.5.5 0 0 1 .5-.5z");
  fill: currentColor;
}

</style>
