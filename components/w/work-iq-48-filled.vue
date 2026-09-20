<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zt0pmacct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:work-iq-48-filled" /></template>
<style>
.zt0pmacct {
  fill: currentColor;
  d: path("M24 6c11.046 0 20 8.954 20 20c0 5.125-3.086 9.528-7.5 11.457V28.5A7.5 7.5 0 1 0 29 36h1.25a1.25 1.25 0 1 0 0-2.5H29a5 5 0 1 1 5-5V39q.002.257.097.481A5 5 0 0 0 39 43.5h1.25a1.25 1.25 0 1 1 0 2.5H39a7.5 7.5 0 0 1-7.5-7.5H29a9.96 9.96 0 0 1-6.611-2.5H13a9 9 0 0 1-9-9v-1C4 14.954 12.954 6 24 6");
}

</style>
