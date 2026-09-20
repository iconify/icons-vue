<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="lbulbecve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:search-28-regular" /></template>
<style>
.lbulbecve {
  fill: currentColor;
  d: path("M18.666 19.727A9.46 9.46 0 0 1 12.5 22a9.5 9.5 0 1 1 9.5-9.5a9.46 9.46 0 0 1-2.273 6.166l6.053 6.054a.75.75 0 1 1-1.06 1.06zM20.5 12.5a8 8 0 1 0-16 0a8 8 0 0 0 16 0");
}

</style>
