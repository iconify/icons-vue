<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="v3stq_vxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:timer-32-regular" /></template>
<style>
.v3stq_vxe {
  fill: currentColor;
  d: path("M13 2a1 1 0 1 0 0 2h6a1 1 0 1 0 0-2zm3 9a1 1 0 0 1 1 1v6a1 1 0 1 1-2 0v-6a1 1 0 0 1 1-1m12 7c0 6.627-5.373 12-12 12S4 24.627 4 18S9.373 6 16 6s12 5.373 12 12m-2 0c0-5.523-4.477-10-10-10S6 12.477 6 18s4.477 10 10 10s10-4.477 10-10m.708-11.707a1 1 0 1 0-1.414 1.414l2 2a1 1 0 1 0 1.414-1.415z");
}

</style>
