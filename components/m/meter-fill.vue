<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o96f9ybcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:meter-fill" /></template>
<style>
.o96f9ybcv {
  fill: currentColor;
  d: path("M15 3a1 1 0 0 1 2 0h2a3 3 0 0 1 3 3v13a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3h2a1 1 0 0 1 2 0ZM7 7v3a1 1 0 0 0 2 0V7a1 1 0 0 0-2 0m4 0v3a1 1 0 0 0 2 0V7a1 1 0 0 0-2 0m4 0v3a1 1 0 0 0 2 0V7a1 1 0 0 0-2 0m1 9H8a1 1 0 0 0 0 2h8a1 1 0 0 0 0-2");
}

</style>
