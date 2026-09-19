<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m81azlbiq"/><path class="wdlwdq4vk"/><circle class="q7znoxdcs"/><path class="gwvf4zbbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-settings-remote" /></template>
<style>
.gwvf4zbbq {
  fill: currentColor;
  d: path("m7.05 6.05l1.41 1.41a5.02 5.02 0 0 1 7.08 0l1.41-1.41C15.68 4.78 13.93 4 12 4s-3.68.78-4.95 2.05M12 0C8.96 0 6.21 1.23 4.22 3.22l1.41 1.41C7.26 3.01 9.51 2 12 2s4.74 1.01 6.36 2.64l1.41-1.41C17.79 1.23 15.04 0 12 0");
}

.m81azlbiq {
  fill: currentColor;
  d: path("M10 21h4V11h-4zm2-9c.55 0 1 .45 1 1s-.45 1-1 1s-1-.45-1-1s.45-1 1-1");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.q7znoxdcs {
  cx: 12px;
  cy: 13px;
  r: 1px;
  fill: currentColor;
}

.wdlwdq4vk {
  fill: currentColor;
  d: path("M15 9H9c-.55 0-1 .45-1 1v12c0 .55.45 1 1 1h6c.55 0 1-.45 1-1V10c0-.55-.45-1-1-1m-1 12h-4V11h4z");
}

</style>
