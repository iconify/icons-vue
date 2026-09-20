<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gtuj59bkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:more-vertical-32-filled" /></template>
<style>
.gtuj59bkl {
  fill: currentColor;
  d: path("M13 7a3 3 0 1 0 6 0a3 3 0 0 0-6 0m0 9a3 3 0 1 0 6 0a3 3 0 0 0-6 0m0 9a3 3 0 1 0 6 0a3 3 0 0 0-6 0");
}

</style>
