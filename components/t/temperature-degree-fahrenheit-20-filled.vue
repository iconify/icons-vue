<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="myb007wry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:temperature-degree-fahrenheit-20-filled" /></template>
<style>
.myb007wry {
  fill: currentColor;
  d: path("M3.5 7a1.5 1.5 0 1 1 3 0a1.5 1.5 0 0 1-3 0M5 4a3 3 0 1 0 0 6a3 3 0 0 0 0-6m5.75 0a.75.75 0 0 0-.75.75v10.5a.75.75 0 0 0 1.5 0V10.5h4.75a.75.75 0 0 0 0-1.5H11.5V5.5h5.25a.75.75 0 0 0 0-1.5z");
}

</style>
