<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rt-jybbid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:shapes-48-filled" /></template>
<style>
.rt-jybbid {
  fill: currentColor;
  d: path("M23.25 15.5h7.603C29.887 8.993 24.276 4 17.5 4C10.044 4 4 10.044 4 17.5c0 6.776 4.993 12.387 11.5 13.353V23.25a7.75 7.75 0 0 1 7.75-7.75m0 2.5A5.25 5.25 0 0 0 18 23.25v15.5c0 2.9 2.35 5.25 5.25 5.25h15.5c2.9 0 5.25-2.35 5.25-5.25v-15.5c0-2.9-2.35-5.25-5.25-5.25z");
}

</style>
