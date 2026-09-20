<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yl5rcztjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:youtube-tv-outline" /></template>
<style>
.yl5rcztjx {
  fill: currentColor;
  d: path("M6 20v-2h12v2Zm-2-3q-.825 0-1.412-.587Q2 15.825 2 15V6q0-.825.588-1.412Q3.175 4 4 4h16q.825 0 1.413.588Q22 5.175 22 6v9q0 .825-.587 1.413Q20.825 17 20 17Zm0-2h16V6H4v9Zm6-1l5.5-3.5L10 7Zm-6 1V6v9Z");
}

</style>
