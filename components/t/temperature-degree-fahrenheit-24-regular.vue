<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cxwchbc6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:temperature-degree-fahrenheit-24-regular" /></template>
<style>
.cxwchbc6b {
  fill: currentColor;
  d: path("M5 8a1.5 1.5 0 1 1 3 0a1.5 1.5 0 0 1-3 0m1.5-3a3 3 0 1 0 0 6a3 3 0 0 0 0-6m5.75 0a.75.75 0 0 0-.75.75v12.5a.75.75 0 0 0 1.5 0V12.5h5.75a.75.75 0 0 0 0-1.5H13V6.5h6.25a.75.75 0 0 0 0-1.5z");
}

</style>
