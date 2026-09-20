<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qnhy74jih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:remove-from-queue-outline-sharp" /></template>
<style>
.qnhy74jih {
  fill: currentColor;
  d: path("M8.5 11.5h7v-1h-7zM9 20v-2H3V4h18v14h-6v2zm-5-3h16V5H4zm0 0V5z");
}

</style>
