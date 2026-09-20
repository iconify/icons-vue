<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="n-5pqbb-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:microphone-chat-28-filled" /></template>
<style>
.n-5pqbb-b {
  fill: currentColor;
  d: path("M25.75 15.25a.75.75 0 0 1 .75.75a7 7 0 0 1-6.25 6.959v2.291a.75.75 0 0 1-1.5 0v-2.291A7 7 0 0 1 12.5 16a.75.75 0 0 1 1.5 0a5.5 5.5 0 0 0 11 0a.75.75 0 0 1 .75-.75M11.501 2a9.48 9.48 0 0 1 7.017 3.097A5 5 0 0 0 14.499 10v4.776a1.75 1.75 0 0 0-3 1.224a7.96 7.96 0 0 0 1.644 4.855a9.46 9.46 0 0 1-5.834-.831l-3.755.94a1.25 1.25 0 0 1-1.516-1.515l.939-3.755A9.46 9.46 0 0 1 2 11.5C2 6.254 6.254 2 11.5 2m8 4a4 4 0 0 1 4 4v6a4 4 0 0 1-8 0v-6a4 4 0 0 1 4-4");
}

</style>
