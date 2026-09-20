<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dprtwbc5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mark-chat-unread-outline-sharp" /></template>
<style>
.dprtwbc5b {
  fill: currentColor;
  d: path("M2 22V2h12.1q-.1.5-.1 1t.1 1H4v13.125L5.15 16H20V7.9q.575-.125 1.075-.337T22 7v11H6zM4 4v12zm12.875 1.125Q16 4.25 16 3t.875-2.125T19 0t2.125.875T22 3t-.875 2.125T19 6t-2.125-.875");
}

</style>
