<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v62owccja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-rtt" /></template>
<style>
.v62owccja {
  fill: currentColor;
  d: path("m9.03 3l-1.11 7.07h2.62l.7-4.5h2.58L11.8 18.43H9.47L9.06 21h7.27l.4-2.57h-2.35l2-12.86h2.58l-.71 4.5h2.65L22 3zM8 5H4l-.31 2h4zm-.61 4h-4l-.31 2h4zm.92 8h-6L2 19h6zm.62-4h-6l-.31 2h6.01z");
}

</style>
