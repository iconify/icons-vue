<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="xzqeq2bca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:open-12-regular" /></template>
<style>
.xzqeq2bca {
  fill: currentColor;
  d: path("M4 3a1 1 0 0 0-1 1v4a1 1 0 0 0 1 1h4a1 1 0 0 0 1-1V7a.5.5 0 0 1 1 0v1a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2V4a2 2 0 0 1 2-2h1a.5.5 0 0 1 0 1zm3 0a.5.5 0 0 1 0-1h2.5a.5.5 0 0 1 .5.5V5a.5.5 0 0 1-1 0V3.707L7.354 5.354a.5.5 0 1 1-.708-.708L8.293 3z");
}

</style>
