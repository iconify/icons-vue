<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="t1nblxb-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:scan-thin" /></template>
<style>
.t1nblxb-y {
  fill: currentColor;
  d: path("M220 40v40a4 4 0 0 1-8 0V44h-36a4 4 0 0 1 0-8h40a4 4 0 0 1 4 4M80 212H44v-36a4 4 0 0 0-8 0v40a4 4 0 0 0 4 4h40a4 4 0 0 0 0-8m136-40a4 4 0 0 0-4 4v36h-36a4 4 0 0 0 0 8h40a4 4 0 0 0 4-4v-40a4 4 0 0 0-4-4M40 84a4 4 0 0 0 4-4V44h36a4 4 0 0 0 0-8H40a4 4 0 0 0-4 4v40a4 4 0 0 0 4 4m40-8h96a4 4 0 0 1 4 4v96a4 4 0 0 1-4 4H80a4 4 0 0 1-4-4V80a4 4 0 0 1 4-4m4 96h88V84H84Z");
}

</style>
