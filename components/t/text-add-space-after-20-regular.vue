<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pwy1q8bob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-add-space-after-20-regular" /></template>
<style>
.pwy1q8bob {
  fill: currentColor;
  d: path("M3 5.5a.5.5 0 0 1 .5-.5h13a.5.5 0 0 1 0 1h-13a.5.5 0 0 1-.5-.5m0 4a.5.5 0 0 1 .5-.5h13a.5.5 0 0 1 0 1h-13a.5.5 0 0 1-.5-.5m5.146 5.146a.5.5 0 0 0 .708.708L10 14.207l1.146 1.147a.5.5 0 0 0 .708-.708l-1.5-1.5a.5.5 0 0 0-.708 0z");
}

</style>
