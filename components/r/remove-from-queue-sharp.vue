<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wmrr7ib5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:remove-from-queue-sharp" /></template>
<style>
.wmrr7ib5e {
  fill: currentColor;
  d: path("M8.5 11.5h7v-1h-7zM9 20v-2H3V4h18v14h-6v2z");
}

</style>
