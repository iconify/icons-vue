<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="g6jl5qbfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:paint-brush-20-regular" /></template>
<style>
.g6jl5qbfw {
  fill: currentColor;
  d: path("M5.5 1.999a.5.5 0 0 0-.5.5v8.504a2 2 0 0 0 2 2h1.004v2.998a2 2 0 1 0 4 0v-2.998H13a2 2 0 0 0 2-2V2.5a.5.5 0 0 0-.5-.5zm.5 8.004h8v1a1 1 0 0 1-1 1h-1.496a.5.5 0 0 0-.5.5v3.498a1 1 0 1 1-2 0v-3.498a.5.5 0 0 0-.5-.5H7a1 1 0 0 1-1-1zm8-1H6V3h4v1.5a.5.5 0 0 0 1 0V3h1v2.502a.5.5 0 0 0 1 0V3h1z");
}

</style>
