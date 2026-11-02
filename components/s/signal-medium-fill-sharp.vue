<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y8yi0vlry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:signal-medium-fill-sharp" /></template>
<style>
.y8yi0vlry {
  fill: currentColor;
  d: path("M13 20V8a1 1 0 0 1 2 0v12a1 1 0 0 1-2 0m-4 0v-8a1 1 0 0 1 2 0v8a1 1 0 0 1-2 0m-4 0v-4a1 1 0 0 1 2 0v4a1 1 0 0 1-2 0m13-1h.01a1 1 0 0 1 0 2H18a1 1 0 0 1 0-2");
}

</style>
