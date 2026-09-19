<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ffv05rb7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-battery-alert" /></template>
<style>
.ffv05rb7v {
  fill: currentColor;
  d: path("M17 4h-3V2h-4v2H7v18h10zm-4 14h-2v-2h2zm0-4h-2V9h2z");
}

</style>
