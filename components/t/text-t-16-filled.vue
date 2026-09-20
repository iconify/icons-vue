<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="atzfbjl7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-t-16-filled" /></template>
<style>
.atzfbjl7h {
  fill: currentColor;
  d: path("M2.5 2.75A.75.75 0 0 1 3.25 2h9a.75.75 0 0 1 .75.75v1.5a.75.75 0 0 1-1.5 0V3.5h-3v9h1.25a.75.75 0 0 1 0 1.5h-4a.75.75 0 0 1 0-1.5H7v-9H4v.75a.75.75 0 0 1-1.5 0z");
}

</style>
