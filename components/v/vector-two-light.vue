<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="b8v5vh-xj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:vector-two-light" /></template>
<style>
.b8v5vh-xj {
  fill: currentColor;
  d: path("m228.24 196.24l-32 32a6 6 0 0 1-8.48-8.48L209.51 198H80a6 6 0 0 1-6-6V54.49L52.24 76.24a6 6 0 0 1-8.48-8.48l32-32a6 6 0 0 1 8.48 0l32 32a6 6 0 1 1-8.48 8.48L86 54.49V186h123.51l-21.75-21.76a6 6 0 0 1 8.48-8.48l32 32a6 6 0 0 1 0 8.48");
}

</style>
