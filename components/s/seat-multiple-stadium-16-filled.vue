<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="thf37u_wy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:seat-multiple-stadium-16-filled" /></template>
<style>
.thf37u_wy {
  fill: currentColor;
  d: path("M4 12a1 1 0 1 1 0 2H2a1 1 0 1 1 0-2zm5 0a1 1 0 1 1 0 2H7a1 1 0 1 1 0-2zm5 0a1 1 0 1 1 0 2h-2a1 1 0 1 1 0-2zM3 7a2 2 0 0 1 2 2v2.27A2 2 0 0 0 4 11H2c-.365 0-.706.1-1 .27V9a2 2 0 0 1 2-2m5 0c1.09 0 2 .916 2 2v2.27A2 2 0 0 0 9 11H7c-.365 0-.706.1-1 .27V9c0-1.085.905-2 2-2m5 0a2 2 0 0 1 2 2v2.27a2 2 0 0 0-1-.27h-2c-.365 0-.706.1-1 .27V9a2 2 0 0 1 2-2M5.25 2A2.25 2.25 0 0 1 7.5 4.25v1.791a3 3 0 0 0-2 1.302A3 3 0 0 0 3 6V4.25A2.25 2.25 0 0 1 5.25 2m5.5 0A2.25 2.25 0 0 1 13 4.25V6a3 3 0 0 0-2.5 1.343a3 3 0 0 0-2-1.302V4.25A2.25 2.25 0 0 1 10.75 2");
}

</style>
