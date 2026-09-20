<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uymbcac8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:tv-next-outline" /></template>
<style>
.uymbcac8n {
  fill: currentColor;
  d: path("M19.5 22.5L18 21l3-3l-3-3l1.5-1.5L24 18zM8 21v-2H4q-.825 0-1.412-.587T2 17V5q0-.825.588-1.412T4 3h16q.825 0 1.413.588T22 5v7h-2V5H4v12h13v2h-2v2zm-4-4V5z");
}

</style>
