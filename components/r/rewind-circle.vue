<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="xec1-shjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:rewind-circle" /></template>
<style>
.xec1-shjo {
  fill: currentColor;
  d: path("M128 24a104 104 0 1 0 104 104A104.11 104.11 0 0 0 128 24m0 192a88 88 0 1 1 88-88a88.1 88.1 0 0 1-88 88M115.58 84.84a8 8 0 0 0-8.38.76l-48 36a8 8 0 0 0 0 12.8l48 36a8 8 0 0 0 4.8 1.6a8 8 0 0 0 8-8V92a8 8 0 0 0-4.42-7.16M104 148l-26.67-20L104 108Zm75.58-63.16a8 8 0 0 0-8.38.76l-48 36a8 8 0 0 0 0 12.8l48 36a8 8 0 0 0 4.8 1.6a8 8 0 0 0 8-8V92a8 8 0 0 0-4.42-7.16M168 148l-26.67-20L168 108Z");
}

</style>
