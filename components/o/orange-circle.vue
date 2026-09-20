<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<circle class="wttrm1bek"/><circle class="xy08lfu8u"/><path class="bd4az7ajy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:orange-circle" /></template>
<style>
.bd4az7ajy {
  fill: var(--svg-color--ffbd52, #ffbd52);
  d: path("M23.93 29.7c4.5-7.1 14.1-13 24.1-14.8c2.5-.4 5-.6 7.1.2c1.6.6 2.9 2.1 2 3.8c-.7 1.4-2.6 2-4.1 2.5a44.64 44.64 0 0 0-23 17.4c-2 3-5 11.3-8.7 9.2c-3.9-2.3-3.1-9.5 2.6-18.3");
}

.wttrm1bek {
  cx: 63.93px;
  cy: 64px;
  r: 60px;
  fill: var(--svg-color--f77e00, #f77e00);
}

.xy08lfu8u {
  cx: 60.03px;
  cy: 63.1px;
  r: 56.1px;
  fill: var(--svg-color--ff9800, #ff9800);
}

</style>
