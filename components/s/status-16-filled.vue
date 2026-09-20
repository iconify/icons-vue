<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x2f787bfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:status-16-filled" /></template>
<style>
.x2f787bfj {
  fill: currentColor;
  d: path("M14.354 1.647a2.27 2.27 0 0 0-3.207 0l-4.25 4.25a.5.5 0 0 0-.121.195l-1.25 3.75a.5.5 0 0 0 .632.633l3.75-1.25a.5.5 0 0 0 .196-.121l4.25-4.25a2.27 2.27 0 0 0 0-3.207m-1.367 5.988Q13 7.815 13 8a5 5 0 1 1-4.635-4.987l.884-.883a6 6 0 1 0 4.621 4.621z");
}

</style>
