<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="y0f48lb4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:markdown-28-filled" /></template>
<style>
.y0f48lb4m {
  fill: currentColor;
  d: path("M15.293 6.293A1 1 0 0 1 17 7v13a1 1 0 1 1-2 0V9.414l-4.793 4.793a1 1 0 0 1-1.414 0L4 9.414V20a1 1 0 1 1-2 0V7a1 1 0 0 1 1.707-.707L9.5 12.086zM23 6a1 1 0 0 1 1 1v10.586l1.293-1.293a1 1 0 1 1 1.414 1.414l-3 3a1 1 0 0 1-1.414 0l-3-3a1 1 0 1 1 1.414-1.414L22 17.586V7a1 1 0 0 1 1-1");
}

</style>
