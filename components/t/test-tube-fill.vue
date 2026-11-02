<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u07sl8b-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:test-tube-fill" /></template>
<style>
.u07sl8b-z {
  fill: currentColor;
  d: path("M17 2a1 1 0 0 1 0 2h-1v14a4.002 4.002 0 0 1-6.002 3.463A4 4 0 0 1 8 18V4H7a1 1 0 0 1 0-2Zm-7 9h4V4h-4Z");
}

</style>
