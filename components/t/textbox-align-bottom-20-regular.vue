<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qxvfgccms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:textbox-align-bottom-20-regular" /></template>
<style>
.qxvfgccms {
  fill: currentColor;
  d: path("M13.5 10a.5.5 0 0 1 0 1h-7a.5.5 0 0 1 0-1zm0 3h-7a.5.5 0 0 0 0 1h7a.5.5 0 0 0 0-1m3.5 1.5a2.5 2.5 0 0 1-2.5 2.5h-9A2.5 2.5 0 0 1 3 14.5v-9A2.5 2.5 0 0 1 5.5 3h9A2.5 2.5 0 0 1 17 5.5zM5.5 16h9a1.5 1.5 0 0 0 1.5-1.5v-9A1.5 1.5 0 0 0 14.5 4h-9A1.5 1.5 0 0 0 4 5.5v9A1.5 1.5 0 0 0 5.5 16");
}

</style>
