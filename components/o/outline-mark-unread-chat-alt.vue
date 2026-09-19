<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oxfxxo94r"/><circle class="ov-wf5bce"/><path class="agc55zb2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-mark-unread-chat-alt" /></template>
<style>
.agc55zb2t {
  fill: currentColor;
  d: path("M6 12h8v2H6zm0-3h12v2H6zm0-1h12v-.1A5 5 0 0 1 15.03 6H6z");
}

.ov-wf5bce {
  cx: 19px;
  cy: 3px;
  r: 3px;
  fill: currentColor;
}

.oxfxxo94r {
  fill: currentColor;
  d: path("M20 16H4V4h10.1a5 5 0 0 1 0-2H4c-1.1 0-2 .9-2 2v18l4-4h14c1.1 0 2-.9 2-2V6.98c-.58.44-1.26.77-2 .92z");
}

</style>
