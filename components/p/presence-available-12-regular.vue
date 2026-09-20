<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="gb2mlgi3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:presence-available-12-regular" /></template>
<style>
.gb2mlgi3z {
  fill: currentColor;
  d: path("M6 0a6 6 0 1 0 0 12A6 6 0 0 0 6 0M1.5 6a4.5 4.5 0 1 1 9 0a4.5 4.5 0 0 1-9 0m7.03-1.78a.75.75 0 0 1 0 1.06L5.78 8.03a.75.75 0 0 1-1.06 0l-1-1a.75.75 0 0 1 1.06-1.06l.47.47l2.22-2.22a.75.75 0 0 1 1.06 0");
}

</style>
