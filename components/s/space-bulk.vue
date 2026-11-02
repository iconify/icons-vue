<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o_ahxnbky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:space-bulk" /></template>
<style>
.o_ahxnbky {
  fill: currentColor;
  d: path("M5 13a.997.997 0 0 0 1 1h12a1 1 0 0 0 1-1V9a1 1 0 0 1 2 0v4a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3V9a1 1 0 0 1 2 0Z");
}

</style>
