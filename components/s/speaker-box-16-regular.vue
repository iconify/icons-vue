<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kb2dxacaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:speaker-box-16-regular" /></template>
<style>
.kb2dxacaw {
  fill: currentColor;
  d: path("M3 3.5A2.5 2.5 0 0 1 5.5 1h5A2.5 2.5 0 0 1 13 3.5v9a2.5 2.5 0 0 1-2.5 2.5h-5A2.5 2.5 0 0 1 3 12.5zM5.5 2A1.5 1.5 0 0 0 4 3.5v9A1.5 1.5 0 0 0 5.5 14h5a1.5 1.5 0 0 0 1.5-1.5v-9A1.5 1.5 0 0 0 10.5 2zM8 8.5a1.5 1.5 0 1 0 0 3a1.5 1.5 0 0 0 0-3M5.5 10a2.5 2.5 0 1 1 5 0a2.5 2.5 0 0 1-5 0M8 6a1 1 0 1 0 0-2a1 1 0 0 0 0 2");
}

</style>
