<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="wc3_yub7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:rename-28-filled" /></template>
<style>
.wc3_yub7v {
  fill: currentColor;
  d: path("M11.75 2a.75.75 0 0 0 0 1.5h1.5v21h-1.5a.75.75 0 0 0 0 1.5h4.5a.75.75 0 0 0 0-1.5h-1.5v-21h1.5a.75.75 0 0 0 0-1.5zm-5.5 4.02h6v16h-6A3.25 3.25 0 0 1 3 18.77v-9.5a3.25 3.25 0 0 1 3.25-3.25m15.5 16h-6v-16h6A3.25 3.25 0 0 1 25 9.27v9.5a3.25 3.25 0 0 1-3.25 3.25");
}

</style>
