<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="yfz3w9lrl"/><path class="wwckf8xog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-emoji-people" /></template>
<style>
.wwckf8xog {
  fill: currentColor;
  d: path("M15.89 8.11C15.5 7.72 14.83 7 13.53 7h-2.54a5.02 5.02 0 0 1-4.92-4.15A1 1 0 0 0 5.09 2c-.61 0-1.09.54-1 1.14A7.04 7.04 0 0 0 9 8.71V21c0 .55.45 1 1 1s1-.45 1-1v-5h2v5c0 .55.45 1 1 1s1-.45 1-1V10.05l3.24 3.24a.996.996 0 1 0 1.41-1.41z");
}

.yfz3w9lrl {
  cx: 12px;
  cy: 4px;
  r: 2px;
  fill: currentColor;
}

</style>
