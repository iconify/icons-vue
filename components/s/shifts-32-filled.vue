<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="g03ozac8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:shifts-32-filled" /></template>
<style>
.g03ozac8g {
  fill: currentColor;
  d: path("M4 9a5 5 0 0 1 5-5h14a5 5 0 0 1 5 5v14a5 5 0 0 1-5 5H9a5 5 0 0 1-5-5zm12.006 0a1 1 0 0 0-2 0v8a1 1 0 0 0 1 1h6a1 1 0 0 0 0-2h-5z");
}

</style>
