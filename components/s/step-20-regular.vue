<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hdru7dbqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:step-20-regular" /></template>
<style>
.hdru7dbqq {
  fill: currentColor;
  d: path("M12 3a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v12a3 3 0 0 1-3 3H3a1 1 0 0 1-1-1v-4a1 1 0 0 1 1-1h4V8a1 1 0 0 1 1-1h4zm5 0h-4v4a1 1 0 0 1-1 1H8v4a1 1 0 0 1-1 1H3v4h12a2 2 0 0 0 2-2z");
}

</style>
