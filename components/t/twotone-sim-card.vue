<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zfmjpbbnd"/><path class="hk2p2ybqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-sim-card" /></template>
<style>
.hk2p2ybqs {
  fill: currentColor;
  d: path("M18 2h-8L4 8v12c0 1.1.9 2 2 2h12c1.1 0 2-.9 2-2V4c0-1.1-.9-2-2-2m0 2v16H6V8.83L10.83 4zM7 17h2v2H7zm8 0h2v2h-2zm-8-6h2v4H7zm4 4h2v4h-2zm0-4h2v2h-2zm4 0h2v4h-2z");
}

.zfmjpbbnd {
  fill: currentColor;
  d: path("M6 8.83V20h12V4h-7.17zM9 19H7v-2h2zm0-4H7v-4h2zm6-4h2v4h-2zm0 6h2v2h-2zm-4-6h2v2h-2zm0 4h2v4h-2z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
