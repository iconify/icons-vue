<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xwfuv6b5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:notebook-error-20-filled" /></template>
<style>
.xwfuv6b5u {
  fill: currentColor;
  d: path("M3 4a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2v12a2 2 0 0 1-2 2H9.743A5.5 5.5 0 0 0 3 9.6zm2.5 1a.5.5 0 0 0-.5.5v1a.5.5 0 0 0 .5.5h7a.5.5 0 0 0 .5-.5v-1a.5.5 0 0 0-.5-.5zm11 1H16v2.5h.5A.5.5 0 0 0 17 8V6.5a.5.5 0 0 0-.5-.5M16 9.5h.5a.5.5 0 0 1 .5.5v1.5a.5.5 0 0 1-.5.5H16zm.5 3.5H16v2.5h.5a.5.5 0 0 0 .5-.5v-1.5a.5.5 0 0 0-.5-.5m-11 6a4.5 4.5 0 1 0 0-9a4.5 4.5 0 0 0 0 9M5 12.5a.5.5 0 0 1 1 0v2a.5.5 0 0 1-1 0zm1.125 4a.625.625 0 1 1-1.25 0a.625.625 0 0 1 1.25 0");
}

</style>
