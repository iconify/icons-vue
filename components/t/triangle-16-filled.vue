<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="miy6bfbkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:triangle-16-filled" /></template>
<style>
.miy6bfbkx {
  fill: currentColor;
  d: path("M6.687 1.777a1.5 1.5 0 0 1 2.629 0l5.499 9.999a1.5 1.5 0 0 1-1.314 2.223H2.502a1.5 1.5 0 0 1-1.314-2.223z");
}

</style>
