<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b2sifu3ru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-view-timeline" /></template>
<style>
.b2sifu3ru {
  fill: currentColor;
  d: path("M21 3H3v18h18zm-9 14H6v-2h6zm3-4H9v-2h6zm3-4h-6V7h6z");
}

</style>
