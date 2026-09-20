<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wxg0ulboe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:more-vertical-20-filled" /></template>
<style>
.wxg0ulboe {
  fill: currentColor;
  d: path("M10 6.5A1.75 1.75 0 1 1 10 3a1.75 1.75 0 0 1 0 3.5M10 17a1.75 1.75 0 1 1 0-3.5a1.75 1.75 0 0 1 0 3.5m-1.75-7a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 0 0-3.5 0");
}

</style>
