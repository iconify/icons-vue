<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="er07hpbwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:pause-circle" /></template>
<style>
.er07hpbwm {
  fill: currentColor;
  d: path("M128 24a104 104 0 1 0 104 104A104.11 104.11 0 0 0 128 24m0 192a88 88 0 1 1 88-88a88.1 88.1 0 0 1-88 88M112 96v64a8 8 0 0 1-16 0V96a8 8 0 0 1 16 0m48 0v64a8 8 0 0 1-16 0V96a8 8 0 0 1 16 0");
}

</style>
