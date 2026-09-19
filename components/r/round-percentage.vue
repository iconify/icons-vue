<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tw2rh4zot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-percentage" /></template>
<style>
.tw2rh4zot {
  fill: currentColor;
  d: path("M17.503 4.498L4.499 17.503a1.411 1.411 0 0 0 1.996 1.996L19.499 6.495a1.412 1.412 0 0 0-1.996-1.997M7.002 5a2 2 0 1 0-.004 4a2 2 0 0 0 .004-4m10 10a2 2 0 1 0-.004 4a2 2 0 0 0 .004-4");
}

</style>
