<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bhs8mxbri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:octagon-help-fill-sharp" /></template>
<style>
.bhs8mxbri {
  fill: currentColor;
  d: path("M8 2h8c.265 0 .52.105.707.293l5 5A1 1 0 0 1 22 8v8c0 .265-.105.52-.293.707l-5 5A1 1 0 0 1 16 22H8a1 1 0 0 1-.707-.293l-5-5A1 1 0 0 1 2 16V8c0-.265.105-.52.293-.707l5-5A1 1 0 0 1 8 2m0 9a1 1 0 0 0 2 0a2 2 0 1 1 2 2a1 1 0 0 0 0 2a4 4 0 1 0-4-4m4 5a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Z");
}

</style>
