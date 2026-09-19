<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o5bc4hkkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-sync-problem" /></template>
<style>
.o5bc4hkkn {
  fill: currentColor;
  d: path("M3 12c0 2.21.91 4.2 2.36 5.64L3 20h6v-6l-2.24 2.24A6 6 0 0 1 5 12a5.99 5.99 0 0 1 4-5.65V4.26C5.55 5.15 3 8.27 3 12m8 5h2v-2h-2zM21 4h-6v6l2.24-2.24A6 6 0 0 1 19 12a5.99 5.99 0 0 1-4 5.65v2.09c3.45-.89 6-4.01 6-7.74c0-2.21-.91-4.2-2.36-5.64zm-10 9h2V7h-2z");
}

</style>
