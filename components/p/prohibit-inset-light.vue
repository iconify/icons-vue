<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="wg9yhukfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:prohibit-inset-light" /></template>
<style>
.wg9yhukfp {
  fill: currentColor;
  d: path("M164.24 155.76a6 6 0 1 1-8.48 8.48l-64-64a6 6 0 0 1 8.48-8.48ZM230 128A102 102 0 1 1 128 26a102.12 102.12 0 0 1 102 102m-12 0a90 90 0 1 0-90 90a90.1 90.1 0 0 0 90-90");
}

</style>
