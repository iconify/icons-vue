<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vi26ue4fy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-arrow-down-fill" /></template>
<style>
.vi26ue4fy {
  fill: currentColor;
  d: path("M2 5a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Zm6.293 8.707l3 3a1 1 0 0 0 1.414 0l3-3a.999.999 0 1 0-1.414-1.414L13 13.586V8a1 1 0 0 0-2 0v5.586l-1.293-1.293a.999.999 0 1 0-1.414 1.414");
}

</style>
