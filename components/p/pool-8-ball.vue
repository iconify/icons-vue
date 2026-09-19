<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="xapvc125w"/><ellipse transform="rotate(-39.592 36.265 24.268)" class="te_iatbor"/><path class="jtfex63xm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:pool-8-ball" /></template>
<style>
.jtfex63xm {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M45.3 23.2c1.8 2.9.8 6.3-2.9 8.6s-7.2 1.7-9-1.2c-1.1-1.8-1.1-3.8 0-5.6c-1.7 0-3.1-.7-4.1-2.2c-1.7-2.7-.7-6 2.5-7.9c3.1-1.9 6.5-1.4 8.2 1.3c1 1.6 1 3.2.2 4.6c2.1-.3 3.9.6 5.1 2.4m-3.1 1.6c-.9-1.5-2.9-1.9-4.6-.8c-1.8 1.1-2.3 3-1.4 4.5c1 1.6 2.9 2 4.7.9c1.7-1.1 2.2-3.1 1.3-4.6M32 21.3c.9 1.4 2.7 1.9 4.3.8c1.6-1 2-2.8 1.1-4.2s-2.7-1.8-4.3-.8c-1.5 1-1.9 2.7-1.1 4.2");
}

.te_iatbor {
  cx: 36.3px;
  cy: 24.3px;
  fill: var(--svg-color--f5f5f5, #f5f5f5);
  rx: 13.1px;
  ry: 13.9px;
}

.xapvc125w {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--333, #333);
}

</style>
