<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dppxk3b4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mark-unread-chat-alt-sharp" /></template>
<style>
.dppxk3b4k {
  fill: currentColor;
  d: path("M16.875 5.125Q16 4.25 16 3t.875-2.125T19 0t2.125.875T22 3t-.875 2.125T19 6t-2.125-.875M2 22V2h12.1q-.1.5-.1 1t.1 1q.125.575.35 1.075T15 6H6v2h13q.8 0 1.575-.25T22 7v11H6zm4-11h12V9H6zm0 3h8v-2H6z");
}

</style>
