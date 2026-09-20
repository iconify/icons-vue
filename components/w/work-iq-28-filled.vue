<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="x43kdbb2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:work-iq-28-filled" /></template>
<style>
.x43kdbb2g {
  fill: currentColor;
  d: path("M14 3c6.627 0 12 5.373 12 12a7.5 7.5 0 0 1-4.5 6.874V16.5A4.5 4.5 0 1 0 17 21h.75a.75.75 0 0 0 0-1.5H17a3 3 0 1 1 3-3v6a3 3 0 0 0 3 3h.75a.75.75 0 0 1 0 1.5H23a4.5 4.5 0 0 1-4.5-4.5H17a5.98 5.98 0 0 1-3.967-1.5H7.25A5.25 5.25 0 0 1 2 15.75V15C2 8.373 7.373 3 14 3");
}

</style>
