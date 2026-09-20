<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="pg4szgygv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:spiral-thin" /></template>
<style>
.pg4szgygv {
  fill: currentColor;
  d: path("M244 144a4 4 0 0 1-8 0A100.11 100.11 0 0 0 136 44a92.1 92.1 0 0 0-92 92a84.09 84.09 0 0 0 84 84a76.08 76.08 0 0 0 76-76a68.07 68.07 0 0 0-68-68a60.07 60.07 0 0 0-60 60a52.06 52.06 0 0 0 52 52a44.05 44.05 0 0 0 44-44a36 36 0 0 0-36-36a28 28 0 0 0-28 28a20 20 0 0 0 20 20a12 12 0 0 0 12-12a4 4 0 0 0-4-4a4 4 0 0 1 0-8a12 12 0 0 1 12 12a20 20 0 0 1-20 20a28 28 0 0 1-28-28a36 36 0 0 1 36-36a44.05 44.05 0 0 1 44 44a52.06 52.06 0 0 1-52 52a60.07 60.07 0 0 1-60-60a68.07 68.07 0 0 1 68-68a76.08 76.08 0 0 1 76 76a84.09 84.09 0 0 1-84 84a92.1 92.1 0 0 1-92-92A100.11 100.11 0 0 1 136 36a108.12 108.12 0 0 1 108 108");
}

</style>
