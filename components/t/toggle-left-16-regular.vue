<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wcrhzya1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:toggle-left-16-regular" /></template>
<style>
.wcrhzya1l {
  fill: currentColor;
  d: path("M5 10a2 2 0 1 1 0-4a2 2 0 0 1 0 4m10-2a4 4 0 0 0-4-4H5a4 4 0 1 0 0 8h6a4 4 0 0 0 4-4m-4-3a3 3 0 1 1 0 6H5a3 3 0 0 1 0-6z");
}

</style>
