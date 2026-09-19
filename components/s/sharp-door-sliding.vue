<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qqdavsb6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-door-sliding" /></template>
<style>
.qqdavsb6c {
  fill: currentColor;
  d: path("M20 19V3h-7.25v16h-1.5V3H4v16H3v2h18v-2zm-10-6H8v-2h2zm6 0h-2v-2h2z");
}

</style>
