<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xp7upo5om"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:star-three-quarter-16-filled" /></template>
<style>
.xp7upo5om {
  fill: currentColor;
  d: path("M7.194 2.101a.9.9 0 0 1 1.614 0L10 4.517V13.4l-1.999-1.051l-3.042 1.599a.9.9 0 0 1-1.306-.949l.58-3.387l-2.46-2.4a.9.9 0 0 1 .499-1.534l3.4-.495z");
}

</style>
