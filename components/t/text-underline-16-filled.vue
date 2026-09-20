<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="by7j-ezcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-underline-16-filled" /></template>
<style>
.by7j-ezcx {
  fill: currentColor;
  d: path("M4 13.75a.75.75 0 0 1 .75-.75h6.5a.75.75 0 0 1 0 1.5h-6.5a.75.75 0 0 1-.75-.75M4.75 2a.75.75 0 0 1 .75.75V8a2.5 2.5 0 1 0 5 0V2.75a.75.75 0 0 1 1.5 0V8a4 4 0 1 1-8 0V2.75A.75.75 0 0 1 4.75 2");
}

</style>
