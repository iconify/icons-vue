<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rh1curllq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-line-spacing-24-filled" /></template>
<style>
.rh1curllq {
  fill: currentColor;
  d: path("M19 13a1 1 0 0 1 1 1v4.586l.293-.293a1 1 0 1 1 1.414 1.414l-2 2a1 1 0 0 1-1.414 0l-2-2a1 1 0 1 1 1.414-1.414l.293.293V14a1 1 0 0 1 1-1m-9 4a1 1 0 1 1 0 2H3a1 1 0 1 1 0-2zm4-6a1 1 0 1 1 0 2H3a1 1 0 1 1 0-2zm5-9a1 1 0 0 1 .707.293l2 2a1 1 0 1 1-1.414 1.414L20 5.414V10a1 1 0 1 1-2 0V5.414l-.293.293a1 1 0 1 1-1.414-1.414l2-2A1 1 0 0 1 19 2m-9 3a1 1 0 1 1 0 2H3a1 1 0 0 1 0-2z");
}

</style>
