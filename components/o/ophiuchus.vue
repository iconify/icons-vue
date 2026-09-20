<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<circle class="r_e5fnbmx"/><circle class="r7p9g1b3v"/><path class="ho_qqfbkv"/><path class="sho6_mkko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:ophiuchus" /></template>
<style>
.ho_qqfbkv {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 29.7c4.5-7.1 14.1-13 24.1-14.8c2.5-.4 5-.6 7.1.2c1.6.6 2.9 2.1 2 3.8c-.7 1.4-2.6 2-4.1 2.5c-9.3 3-17.9 6.4-23.1 14.3c-2 3-4.9 14.4-8.6 12.3c-3.9-2.3-3.1-9.5 2.6-18.3");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.r_e5fnbmx {
  cx: 64px;
  cy: 64px;
  r: 60px;
  fill: var(--svg-color--0097a7, #0097a7);
}

.r7p9g1b3v {
  cx: 60.1px;
  cy: 63.1px;
  r: 56.1px;
  fill: var(--svg-color--00bcd4, #00bcd4);
}

.sho6_mkko {
  fill: var(--svg-color--fafafa, #fafafa);
  d: path("M101.8 50.3c-.8-1.6-2.5-2.6-4.3-2.6c-.8 0-1.6.2-2.3.6l-2 1c-1.9 1-3.6 1.8-5.2 2.5V32.9c0-2.7-1.9-5-4.4-5.2h-.5c-1.3 0-2.5.5-3.5 1.5c-.9 1-1.4 2.2-1.4 3.6v21.4h-1.7c-2.9 0-5.9-.4-9.3-1.3l-7.3-2c-4.2-1.1-8-1.7-11.7-1.7h-1.6V32.9c0-2.7-1.9-5-4.4-5.2h-.5c-1.3 0-2.5.5-3.5 1.5c-.9 1-1.4 2.2-1.4 3.6V51c-3.1 1-6.2 2.3-9.6 4.1l-3 1.5c-2.2 1.2-3.3 3.9-2.5 6.3c.7 2 2.5 3.4 4.6 3.4c.8 0 1.5-.2 2.2-.6l3.1-1.6c1.8-1 3.5-1.8 5.2-2.5V77c0 15.1 11.4 27.3 25.5 27.3S88 92.2 88 77.1V62.6c3.1-1 6.2-2.3 9.6-4.1l2.2-1.1c2.4-1.4 3.3-4.6 2-7.1M78.2 76.7c0 9.3-6.8 17.2-15.2 17.5h-.6c-8.7 0-15.8-7.7-15.8-17.1V59.4h1.7c2.9 0 5.9.4 9.3 1.3l7.3 2c4.2 1.1 8 1.7 11.7 1.7h1.6z");
}

</style>
