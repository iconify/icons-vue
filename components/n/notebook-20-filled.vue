<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="h-f1i3p4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:notebook-20-filled" /></template>
<style>
.h-f1i3p4b {
  fill: currentColor;
  d: path("M5 2a2 2 0 0 0-2 2v12a2 2 0 0 0 2 2h8a2 2 0 0 0 2-2V4a2 2 0 0 0-2-2zm0 3.5a.5.5 0 0 1 .5-.5h7a.5.5 0 0 1 .5.5v1a.5.5 0 0 1-.5.5h-7a.5.5 0 0 1-.5-.5zM16 6h.5a.5.5 0 0 1 .5.5V8a.5.5 0 0 1-.5.5H16zm0 3.5h.5a.5.5 0 0 1 .5.5v1.5a.5.5 0 0 1-.5.5H16zm0 3.5h.5a.5.5 0 0 1 .5.5V15a.5.5 0 0 1-.5.5H16z");
}

</style>
