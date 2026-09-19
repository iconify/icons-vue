<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="s4qb7j6kb"/><path class="g83y-3pli"/><circle class="mq-ay4bjg"/><circle class="g4f0sxlwt"/><circle class="suf3in2sa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:vertical-traffic-light" /></template>
<style>
.g4f0sxlwt {
  cx: 32px;
  cy: 13.2px;
  r: 7.5px;
  fill: var(--svg-color--ed4c5c, #ed4c5c);
}

.g83y-3pli {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M32 3.9c-7.2 0-13.1 5.9-13.1 13.1v30c0 7.2 5.9 13.1 13.1 13.1S45.1 54.2 45.1 47V17c0-7.2-5.9-13.1-13.1-13.1");
}

.mq-ay4bjg {
  cx: 32px;
  cy: 32px;
  r: 7.5px;
  fill: var(--svg-color--ffe62e, #ffe62e);
}

.s4qb7j6kb {
  fill: var(--svg-color--94989b, #94989b);
  d: path("M32 2c-8.2 0-15 6.8-15 15v30c0 8.3 6.8 15 15 15s15-6.7 15-15V17c0-8.2-6.8-15-15-15");
}

.suf3in2sa {
  cx: 32px;
  cy: 50.8px;
  r: 7.5px;
  fill: var(--svg-color--83bf4f, #83bf4f);
}

</style>
