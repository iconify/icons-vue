<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kfgrg9zie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-align-right-24-filled" /></template>
<style>
.kfgrg9zie {
  fill: currentColor;
  d: path("M5 6a1 1 0 0 1 1-1h15a1 1 0 1 1 0 2H6a1 1 0 0 1-1-1m4 12a1 1 0 0 1 1-1h11a1 1 0 1 1 0 2H10a1 1 0 0 1-1-1m-6-7a1 1 0 1 0 0 2h18a1 1 0 1 0 0-2z");
}

</style>
