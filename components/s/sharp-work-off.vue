<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wi0cxlble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-work-off" /></template>
<style>
.wi0cxlble {
  fill: currentColor;
  d: path("M10 4h4v2h-3.6L22 17.6V6h-6V4c0-1.1-.9-2-2-2h-4c-.98 0-1.79.71-1.96 1.64L10 5.6zM3.4 1.84L1.99 3.25L4.74 6H2.01L2 21h17.74l2 2l1.41-1.41z");
}

</style>
