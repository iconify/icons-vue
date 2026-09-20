<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="zgs0u13aq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:sailboat-fill" /></template>
<style>
.zgs0u13aq {
  fill: currentColor;
  d: path("M160 140V72.85a4 4 0 0 1 7-2.69l55 60.46a8 8 0 0 1 .43 10.26a8.24 8.24 0 0 1-6.58 3.12H164a4 4 0 0 1-4-4m87.21 32.53A8 8 0 0 0 240 168h-96V8a8 8 0 0 0-14.21-5l-104 128A8 8 0 0 0 32 144h96v24H16a8 8 0 0 0-6.25 13l29.6 37a15.93 15.93 0 0 0 12.49 6h152.32a15.93 15.93 0 0 0 12.49-6l29.6-37a8 8 0 0 0 .96-8.47");
}

</style>
