<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zhm75tbgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-italic-24-filled" /></template>
<style>
.zhm75tbgd {
  fill: currentColor;
  d: path("M19 4a1 1 0 1 1 0 2h-3.56l-4.551 12H14a1 1 0 1 1 0 2H5a1 1 0 1 1 0-2h3.75l4.552-12H10a1 1 0 0 1 0-2z");
}

</style>
