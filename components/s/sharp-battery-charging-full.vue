<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pgetemsit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-battery-charging-full" /></template>
<style>
.pgetemsit {
  fill: currentColor;
  d: path("M17 4h-3V2h-4v2H7v18h10zm-6 16v-5.5H9L13 7v5.5h2z");
}

</style>
