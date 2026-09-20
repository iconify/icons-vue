<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="o62drsu2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-direction-rotate-270-right-16-filled" /></template>
<style>
.o62drsu2z {
  fill: currentColor;
  d: path("M11.22 2.22a.75.75 0 0 1 1.06 0l2 2a.75.75 0 1 1-1.06 1.06l-.72-.72v8.69a.75.75 0 0 1-1.5 0V4.56l-.72.72a.75.75 0 0 1-1.06-1.06zM8.486 8.048a.75.75 0 0 1 .528 1.404L7.5 10.02v1.96l1.514.568a.75.75 0 0 1-.528 1.404l-6-2.25l-.104-.049a.75.75 0 0 1 .104-1.355zM4.886 11L6 11.417v-.835zM4.72 2.22a.75.75 0 0 1 1.06 0l2 2a.75.75 0 1 1-1.06 1.06L6 4.56v2.69a.75.75 0 0 1-1.5 0V4.56l-.72.72a.75.75 0 0 1-1.06-1.06z");
}

</style>
