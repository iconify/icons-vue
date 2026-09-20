<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ue_slub7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:ribbon-32-regular" /></template>
<style>
.ue_slub7j {
  fill: currentColor;
  d: path("M16 2C10.477 2 6 6.477 6 12a9.99 9.99 0 0 0 4 8v9a1 1 0 0 0 1.515.858L16 27.166l4.485 2.692A1 1 0 0 0 22 29v-9a9.99 9.99 0 0 0 4-8c0-5.523-4.477-10-10-10M8 12a8 8 0 1 1 16 0a8 8 0 0 1-16 0m12 9.168v6.066l-3.485-2.092a1 1 0 0 0-1.03 0L12 27.234v-6.066A10 10 0 0 0 16 22a10 10 0 0 0 4-.832");
}

</style>
