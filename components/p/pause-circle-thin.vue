<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="rasa6i2st"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:pause-circle-thin" /></template>
<style>
.rasa6i2st {
  fill: currentColor;
  d: path("M128 28a100 100 0 1 0 100 100A100.11 100.11 0 0 0 128 28m0 192a92 92 0 1 1 92-92a92.1 92.1 0 0 1-92 92M108 96v64a4 4 0 0 1-8 0V96a4 4 0 0 1 8 0m48 0v64a4 4 0 0 1-8 0V96a4 4 0 0 1 8 0");
}

</style>
