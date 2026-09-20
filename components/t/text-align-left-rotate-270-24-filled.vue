<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="micmt5b7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-align-left-rotate-270-24-filled" /></template>
<style>
.micmt5b7v {
  fill: currentColor;
  d: path("M6 22a1 1 0 0 1-1-1V6a1 1 0 0 1 2 0v15a1 1 0 0 1-1 1m12 0a1 1 0 0 1-1-1V10a1 1 0 1 1 2 0v11a1 1 0 0 1-1 1m-7-1a1 1 0 1 0 2 0V3a1 1 0 1 0-2 0z");
}

</style>
