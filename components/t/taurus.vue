<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<circle class="h4xt0xbzz"/><circle class="q_dczsb_e"/><path class="ho_qqfbkv"/><path class="zpx-cubri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:taurus" /></template>
<style>
.h4xt0xbzz {
  cx: 64px;
  cy: 64px;
  r: 60px;
  fill: var(--svg-color--e64a19, #e64a19);
}

.ho_qqfbkv {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 29.7c4.5-7.1 14.1-13 24.1-14.8c2.5-.4 5-.6 7.1.2c1.6.6 2.9 2.1 2 3.8c-.7 1.4-2.6 2-4.1 2.5c-9.3 3-17.9 6.4-23.1 14.3c-2 3-4.9 14.4-8.6 12.3c-3.9-2.3-3.1-9.5 2.6-18.3");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.q_dczsb_e {
  cx: 60.1px;
  cy: 63.1px;
  r: 56.1px;
  fill: var(--svg-color--ff7043, #ff7043);
}

.zpx-cubri {
  fill: var(--svg-color--fafafa, #fafafa);
  d: path("M94.8 36.7c.6-1.4.4-3-.5-4.2s-2.3-2-3.8-2H90c-1.9 0-3.6 1.1-4.3 2.9c-3.4 8.5-9.9 12.1-21.8 12.1s-18.4-3.6-21.8-12.1c-.7-1.8-2.4-2.9-4.3-2.9h-.5c-1.5 0-2.9.8-3.8 2s-1 2.8-.5 4.2c2.4 5.8 9 11.9 14.3 15.3c-7.6 5.3-12.6 14.1-12.6 24.1c0 16.2 13.1 29.3 29.3 29.3s29.3-13.1 29.3-29.3c0-10.1-5.1-19-12.9-24.3c5.4-3.4 12.2-9.4 14.4-15.1M64 96.5c-11.2 0-20.3-9.1-20.3-20.3S52.8 55.8 64 55.8s20.3 9.1 20.3 20.3S75.2 96.5 64 96.5");
}

</style>
