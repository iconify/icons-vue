<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bj16x4bwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:microphone-chat-16-filled" /></template>
<style>
.bj16x4bwv {
  fill: currentColor;
  d: path("M15.5 8a.5.5 0 0 1 .5.5a4.5 4.5 0 0 1-4 4.47v1.53a.5.5 0 0 1-1 0v-1.53A4.5 4.5 0 0 1 7 8.5a.5.5 0 0 1 1 0a3.5 3.5 0 1 0 7 0a.5.5 0 0 1 .5-.5M6.502 1c1.357 0 2.599.493 3.558 1.309A3.5 3.5 0 0 0 8 5.5v1.586A1.5 1.5 0 0 0 6 8.5c0 1.308.458 2.508 1.22 3.451a5.5 5.5 0 0 1-3.137-.515l-2.149.54a.75.75 0 0 1-.91-.91L1.56 8.91A5.5 5.5 0 0 1 6.501 1M11.5 3A2.5 2.5 0 0 1 14 5.5v3a2.5 2.5 0 0 1-5 0v-3A2.5 2.5 0 0 1 11.5 3");
}

</style>
