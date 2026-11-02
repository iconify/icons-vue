<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yxyq2gb9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:robot-fill-sharp" /></template>
<style>
.yxyq2gb9i {
  fill: currentColor;
  d: path("M13 5.733V8h6a1 1 0 0 1 1 1v5h1a1 1 0 0 1 0 2h-1v5a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1v-5H3a1 1 0 0 1 0-2h1V9a1 1 0 0 1 1-1h6V5.733a2.001 2.001 0 1 1 2 0M10 15v-2a1 1 0 0 0-2 0v2a1 1 0 0 0 2 0m6 0v-2a1 1 0 0 0-2 0v2a1 1 0 0 0 2 0");
}

</style>
