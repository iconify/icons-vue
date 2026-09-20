<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bm_2uex7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mark-chat-unread-outline" /></template>
<style>
.bm_2uex7w {
  fill: currentColor;
  d: path("M2 22V4q0-.825.588-1.412T4 2h10.1q-.1.5-.1 1t.1 1H4v13.125L5.15 16H20V7.9q.575-.125 1.075-.337T22 7v9q0 .825-.587 1.413T20 18H6zM4 4v12zm12.875 1.125Q16 4.25 16 3t.875-2.125T19 0t2.125.875T22 3t-.875 2.125T19 6t-2.125-.875");
}

</style>
