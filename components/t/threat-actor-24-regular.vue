<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ncjhz1bdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:threat-actor-24-regular" /></template>
<style>
.ncjhz1bdt {
  fill: currentColor;
  d: path("M11.999 2c4.117 0 7.651 2.488 9.185 6.042A2.25 2.25 0 0 1 23 10.25v1c0 .78-.397 1.466-1 1.87v2.93a4.95 4.95 0 0 1-8.45 3.5l-.843-.843a1 1 0 0 0-1.414 0l-.843.843A4.951 4.951 0 0 1 2 16.05v-2.93c-.603-.404-1-1.09-1-1.87v-1a2.25 2.25 0 0 1 1.813-2.207A10 10 0 0 1 12 2M4.836 14.75a2.5 2.5 0 1 0 4.33 2.5zm10 2.5a2.5 2.5 0 0 0 4.33-2.5zM3.25 9.5a.75.75 0 0 0-.75.75v1c0 .414.336.75.75.75h17.5a.75.75 0 0 0 .75-.75v-1a.75.75 0 0 0-.75-.75zm8.749-6A8.5 8.5 0 0 0 4.5 8h14.998a8.5 8.5 0 0 0-7.499-4.5");
}

</style>
