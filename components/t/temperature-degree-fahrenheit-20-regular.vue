<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="t-j3u3b9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:temperature-degree-fahrenheit-20-regular" /></template>
<style>
.t-j3u3b9j {
  fill: currentColor;
  d: path("M4 6.5a1.5 1.5 0 1 1 3 0a1.5 1.5 0 0 1-3 0M5.5 4a2.5 2.5 0 1 0 0 5a2.5 2.5 0 0 0 0-5m5 0a.5.5 0 0 0-.5.5v11a.5.5 0 0 0 1 0V10h5a.5.5 0 0 0 0-1h-5V5h5.5a.5.5 0 0 0 0-1z");
}

</style>
