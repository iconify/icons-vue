<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="quzqgulks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:stream-24-filled" /></template>
<style>
.quzqgulks {
  fill: currentColor;
  d: path("M9 11a7 7 0 0 1 7-7h1.5a1 1 0 1 0 0-2H16a9 9 0 0 0-9 9a1 1 0 0 1-1 1H3a1 1 0 1 0 0 2h3a3 3 0 0 0 3-3m8-3a4 4 0 0 0-4 4a6 6 0 0 1-6 6H3a1 1 0 1 1 0-2h4a4 4 0 0 0 4-4a6 6 0 0 1 6-6h4a1 1 0 1 1 0 2zm1 4a1 1 0 0 0-1 1a9 9 0 0 1-9 9H6a1 1 0 1 1 0-2h2a7 7 0 0 0 7-7a3 3 0 0 1 3-3h3a1 1 0 1 1 0 2z");
}

</style>
