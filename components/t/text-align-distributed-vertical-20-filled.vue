<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nsr5opkvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-align-distributed-vertical-20-filled" /></template>
<style>
.nsr5opkvf {
  fill: currentColor;
  d: path("M3.03 14.72a.75.75 0 0 0-1.06 1.06l2 2a.75.75 0 0 0 1.06 0l2-2a.75.75 0 1 0-1.06-1.06l-.72.72V2.75a.75.75 0 0 0-1.5 0v12.69zM10 18a.75.75 0 0 1-.75-.75V2.75a.75.75 0 0 1 1.5 0v14.5A.75.75 0 0 1 10 18m8.03-12.72a.75.75 0 0 1-1.06 0l-.72-.72v12.69a.75.75 0 0 1-1.5 0V4.56l-.72.72a.75.75 0 1 1-1.06-1.06l2-2a.75.75 0 0 1 1.06 0l2 2a.75.75 0 0 1 0 1.06");
}

</style>
