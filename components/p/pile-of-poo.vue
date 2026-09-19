<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="lvteh6q6l"/><path class="b3ywhmdwh"/><path class="rojcb43xq"/><path class="pjnclqbot"/><circle class="h_84w20kc"/><path class="allb7n36v"/><g class="g2csbibpu"><circle class="w2ye74bzv"/><path class="c54pe1bcu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:pile-of-poo" /></template>
<style>
.allb7n36v {
  fill: var(--svg-color--fff, #fff);
  d: path("M49.6 34.3c0 4-3.2 7.2-7.2 7.2s-7.2-3.2-7.2-7.2s3.2-7.2 7.2-7.2c3.9 0 7.2 3.2 7.2 7.2");
}

.b3ywhmdwh {
  fill: var(--svg-color--9b7861, #9b7861);
  d: path("M31.7 20.9c-9.6 0-24.5 1.1-24.5 12.6c0 16.8 49.5 16.8 49.5 0c.1-11.5-14.8-12.6-25-12.6");
}

.c54pe1bcu {
  d: path("M38 50.6c0 3.3-2.7 6-6 6s-6-2.7-6-6s2.7-6 6-6s6 2.7 6 6");
}

.g2csbibpu {
  fill: var(--svg-color--231f20, #231f20);
}

.h_84w20kc {
  cx: 23.6px;
  cy: 34.3px;
  r: 3.6px;
  fill: var(--svg-color--231f20, #231f20);
}

.lvteh6q6l {
  fill: var(--svg-color--89664c, #89664c);
  d: path("M32.2 36.9C15.1 36.9 2 29.8 2 45.7C2 58.5 18.9 62 31.8 62c15 0 30.2-3.5 30.2-16.3c0-15.9-12.2-8.8-29.8-8.8");
}

.pjnclqbot {
  fill: var(--svg-color--fff, #fff);
  d: path("M28.8 34.3c0 4-3.2 7.2-7.2 7.2s-7.2-3.2-7.2-7.2s3.2-7.2 7.2-7.2s7.2 3.2 7.2 7.2");
}

.rojcb43xq {
  fill: var(--svg-color--a88673, #a88673);
  d: path("M49 16.7C44.4 6.4 22.6 17 26.4 4.5c.6-1.9.5-2.7-.9-2.4C17.7 3.7 12 11.7 14 18.4c6.4 21.4 41.3 12.3 35-1.7");
}

.w2ye74bzv {
  cx: 40.4px;
  cy: 34.3px;
  r: 3.6px;
}

</style>
