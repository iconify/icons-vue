<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="rhvdvboaq"/><circle class="i2m5ds73n"/><path class="quz-kg3-h"/><path class="gfuqpex9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:winking-face" /></template>
<style>
.gfuqpex9n {
  fill: var(--svg-color--664e27, #664e27);
  d: path("M50.2 34.3c-1.7-3.5-4.4-5.3-7-5.3s-5.2 1.8-7 5.3c-.2.4.7 1 1.2.6c1.7-1.3 3.7-1.8 5.8-1.8s4.1.5 5.8 1.8c.4.3 1.3-.3 1.2-.6m-6.1 7.9c-6.9 3.6-16.4 2.9-19.1 2.9c-.7 0-1.2.3-1 .9c2 7 17 7 21.1-2.7c.5-1.1-.3-1.4-1-1.1");
}

.i2m5ds73n {
  cx: 22.3px;
  cy: 31.6px;
  r: 5px;
  fill: var(--svg-color--664e27, #664e27);
}

.quz-kg3-h {
  fill: var(--svg-color--917524, #917524);
  d: path("M51.2 27.5c-3.2-2.7-7.5-3.9-11.7-3.1c-.6.1-1.1-2-.4-2.2c4.8-.9 9.8.5 13.5 3.6c.6.5-1 2.1-1.4 1.7m-26.7-8.7c-4.2-.7-8.5.4-11.7 3.1c-.4.4-2-1.2-1.4-1.7c3.7-3.2 8.7-4.5 13.5-3.6c.7.2.2 2.3-.4 2.2");
}

.rhvdvboaq {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--ffdd67, #ffdd67);
}

</style>
