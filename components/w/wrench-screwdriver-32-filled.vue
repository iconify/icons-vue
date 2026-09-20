<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="h5dxpb6kj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:wrench-screwdriver-32-filled" /></template>
<style>
.h5dxpb6kj {
  fill: currentColor;
  d: path("M21.072 3.629A1 1 0 0 1 22 3h3a1 1 0 0 1 .928.629l1 2.5a1 1 0 0 1 0 .742L26 9.193V16h2a1 1 0 0 1 1 1v3H18v-3a1 1 0 0 1 1-1h2V9.193l-.928-2.322a1 1 0 0 1 0-.742zM8.577 3.525A1 1 0 0 1 9 4.341V9a1 1 0 0 0 2 0V4.341a1 1 0 0 1 1.333-.942A7.002 7.002 0 0 1 13 16.326V26a3 3 0 1 1-6 0v-9.674a7.002 7.002 0 0 1 .667-12.928a1 1 0 0 1 .91.127M18 22v1.5a5.5 5.5 0 1 0 11 0V22z");
}

</style>
