<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qfxp_itrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-expand-32-regular" /></template>
<style>
.qfxp_itrt {
  fill: currentColor;
  d: path("M29 25a1 1 0 1 1 0 2H8a1 1 0 1 1 0-2zM8.75 9a6.75 6.75 0 1 1 0 13.5a6.75 6.75 0 0 1 0-13.5m0 3a.75.75 0 0 0-.75.75V15H5.75a.75.75 0 0 0 0 1.5H8v2.25a.75.75 0 0 0 1.5 0V16.5h2.25a.75.75 0 0 0 0-1.5H9.5v-2.25a.75.75 0 0 0-.75-.75M29 18a1 1 0 1 1 0 2H19a1 1 0 1 1 0-2zm0-7a1 1 0 1 1 0 2H19a1 1 0 1 1 0-2zm0-7a1 1 0 1 1 0 2H8a1 1 0 0 1 0-2z");
}

</style>
