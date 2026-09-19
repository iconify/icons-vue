<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y6f6i6bxw"/><circle class="ov-wf5bce"/><path class="y53iys_5b"/><path class="agc55zb2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-mark-unread-chat-alt" /></template>
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

.y53iys_5b {
  fill: currentColor;
  d: path("M20 16H5.17L4 17.17V4h10.1a5 5 0 0 1 0-2H4c-1.1 0-1.99.9-1.99 2L2 22l4-4h14c1.1 0 2-.9 2-2V6.97c-.58.44-1.26.77-2 .92z");
}

.y6f6i6bxw {
  fill: currentColor;
  d: path("M4 17.17L5.17 16H20V7.9c-.32.06-.66.1-1 .1s-.68-.04-1-.1V8H6V6h9.03c-.44-.58-.77-1.26-.92-2H4zM6 9h12v2H6zm0 3h8v2H6z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
