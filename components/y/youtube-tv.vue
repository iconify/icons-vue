<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z952sackp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:youtube-tv" /></template>
<style>
.z952sackp {
  fill: currentColor;
  d: path("M6 20v-2h12v2Zm-2-3q-.825 0-1.412-.587Q2 15.825 2 15V6q0-.825.588-1.412Q3.175 4 4 4h16q.825 0 1.413.588Q22 5.175 22 6v9q0 .825-.587 1.413Q20.825 17 20 17Zm6-3l5.5-3.5L10 7Z");
}

</style>
