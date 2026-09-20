<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pmkwgbozn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:stack-vertical-32-regular" /></template>
<style>
.pmkwgbozn {
  fill: currentColor;
  d: path("M24.5 3A4.5 4.5 0 0 1 29 7.5V28a1 1 0 1 1-2 0v-6.5a2.5 2.5 0 0 0-2.5-2.5h-17A2.5 2.5 0 0 0 5 21.5V28a1 1 0 1 1-2 0V7.5A4.5 4.5 0 0 1 7.5 3zm-17 9A2.5 2.5 0 0 0 5 14.5v3.258A4.5 4.5 0 0 1 7.5 17h17c.925 0 1.785.28 2.5.758V14.5a2.5 2.5 0 0 0-2.5-2.5zm0-7A2.5 2.5 0 0 0 5 7.5v3.258A4.5 4.5 0 0 1 7.5 10h17c.925 0 1.785.28 2.5.758V7.5A2.5 2.5 0 0 0 24.5 5z");
}

</style>
