<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ymqi0px_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-4k" /></template>
<style>
.ymqi0px_n {
  fill: currentColor;
  d: path("M19 3H5c-1.1 0-2 .9-2 2v14a2 2 0 0 0 2 2h14c1.1 0 2-.9 2-2V5a2 2 0 0 0-2-2m0 16H5V5h14zm-9.5-4H11v-1.49h1V12h-1V9H9.5v3H8V9H6.5v4.5h3zm8.7 0l-2-3l2-3h-1.7l-2 3l2 3zm-3.7-3V9H13v6h1.5z");
}

</style>
