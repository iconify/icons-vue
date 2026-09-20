<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qum7yib-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:office-apps-24-filled" /></template>
<style>
.qum7yib-c {
  fill: currentColor;
  d: path("M12 17a2 2 0 1 1 0 4a2 2 0 0 1 0-4m7 0a2 2 0 1 1 0 4a2 2 0 0 1 0-4M5 17a2 2 0 1 1 0 4a2 2 0 0 1 0-4m7-7a2 2 0 1 1 0 4a2 2 0 0 1 0-4m7 0a2 2 0 1 1 0 4a2 2 0 0 1 0-4M5 10a2 2 0 1 1 0 4a2 2 0 0 1 0-4m7-7a2 2 0 1 1 0 4a2 2 0 0 1 0-4m7 0a2 2 0 1 1 0 4a2 2 0 0 1 0-4M5 3a2 2 0 1 1 0 4a2 2 0 0 1 0-4");
}

</style>
