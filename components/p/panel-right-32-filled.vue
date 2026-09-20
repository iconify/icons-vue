<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yifco8biv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:panel-right-32-filled" /></template>
<style>
.yifco8biv {
  fill: currentColor;
  d: path("M6.5 28A4.5 4.5 0 0 1 2 23.5v-15A4.5 4.5 0 0 1 6.5 4h19A4.5 4.5 0 0 1 30 8.5v15a4.5 4.5 0 0 1-4.5 4.5zm0-22A2.5 2.5 0 0 0 4 8.5v15A2.5 2.5 0 0 0 6.5 26H20V6z");
}

</style>
