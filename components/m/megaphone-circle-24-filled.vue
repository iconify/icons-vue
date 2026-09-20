<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ugf6ymylx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:megaphone-circle-24-filled" /></template>
<style>
.ugf6ymylx {
  fill: currentColor;
  d: path("M12 22c5.523 0 10-4.477 10-10S17.523 2 12 2S2 6.477 2 12s4.477 10 10 10m-4-7.566l-.861-.319a1.75 1.75 0 0 1-1.143-1.641v-.95A1.75 1.75 0 0 1 7.14 9.881l7.501-2.775a1.75 1.75 0 0 1 2.357 1.641v6.5a1.75 1.75 0 0 1-2.357 1.642l-1.434-.531A2.626 2.626 0 0 1 8 15.875zm3.75 1.387v.054a1.125 1.125 0 0 1-2.25 0v-.887z");
}

</style>
