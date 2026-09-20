<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="el8xxnhte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:target-fill" /></template>
<style>
.el8xxnhte {
  fill: currentColor;
  d: path("M221.87 83.16A104.1 104.1 0 1 1 195.67 49l22.67-22.68a8 8 0 0 1 11.32 11.32L167.6 99.71l-37.71 37.71l-23.95 23.95a40 40 0 0 0 62-35.67a8 8 0 1 1 16-.9a56 56 0 0 1-95.5 42.79a56 56 0 0 1 73.13-84.43l22.73-22.77a87.88 87.88 0 1 0 23.13 29.67a8 8 0 0 1 14.44-6.9");
}

</style>
