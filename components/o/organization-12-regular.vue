<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="zvk711blx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:organization-12-regular" /></template>
<style>
.zvk711blx {
  fill: currentColor;
  d: path("M5.5 4.937a2 2 0 1 1 1 0V6h2a1 1 0 0 1 1 1v1.063a2 2 0 1 1-1 0V7h-5v1.063a2 2 0 1 1-1 0V7a1 1 0 0 1 1-1h2zM6 4a1 1 0 1 0 0-2a1 1 0 0 0 0 2m-3 7a1 1 0 1 0 0-2a1 1 0 0 0 0 2m5-1a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

</style>
