<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d9w7hbbci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:space-fill-sharp" /></template>
<style>
.d9w7hbbci {
  fill: currentColor;
  d: path("M5 14h14V9a1 1 0 0 1 2 0v6a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V9a1 1 0 0 1 2 0Z");
}

</style>
