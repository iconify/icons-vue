<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b_r1s_bet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-event-note" /></template>
<style>
.b_r1s_bet {
  fill: currentColor;
  d: path("M17 10H7v2h10zm4-7h-3V1h-2v2H8V1H6v2H3v18h18zm-2 16H5V8h14zm-5-5H7v2h7z");
}

</style>
