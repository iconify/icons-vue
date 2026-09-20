<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g6xb2c7ft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:unpin" /></template>
<style>
.g6xb2c7ft {
  fill: currentColor;
  d: path("M18.825 16L7 4.175V4q0-.825.588-1.413Q8.175 2 9 2h6q.825 0 1.413.587Q17 3.175 17 4v7.25L18.825 14Zm.95 6.6l-6.6-6.6H13v5l-1 1l-1-1v-5H5v-2l2-3V9.825l-5.6-5.6L2.8 2.8l18.375 18.4Z");
}

</style>
