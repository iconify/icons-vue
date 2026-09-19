<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="rhvdvboaq"/><g class="fbp0m0b1e"><circle class="eohmt5ymd"/><circle class="xq4d0pzdg"/></g><path class="yon5nibsw"/><path class="le26jpqgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:worried-face" /></template>
<style>
.eohmt5ymd {
  cx: 20.5px;
  cy: 29.6px;
  r: 5px;
}

.fbp0m0b1e {
  fill: var(--svg-color--664e27, #664e27);
}

.le26jpqgx {
  fill: var(--svg-color--664e27, #664e27);
  d: path("M40.6 44.4c-5.4-2.5-11.8-2.5-17.2 0c-1.3.6.3 4.2 1.7 3.5c3.6-1.7 8.9-2.3 13.9 0c1.3.6 3-2.8 1.6-3.5");
}

.rhvdvboaq {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--ffdd67, #ffdd67);
}

.xq4d0pzdg {
  cx: 43.5px;
  cy: 29.6px;
  r: 5px;
}

.yon5nibsw {
  fill: var(--svg-color--917524, #917524);
  d: path("M51.2 18.7c-3.2-2.7-7.5-3.9-11.7-3.1c-.6.1-1.1-2-.4-2.2c4.8-.9 9.8.5 13.5 3.6c.6.5-1 2.1-1.4 1.7m-26.7-3.3c-4.2-.7-8.5.4-11.7 3.1c-.4.4-2-1.2-1.4-1.7c3.7-3.2 8.7-4.5 13.5-3.6c.7.2.2 2.4-.4 2.2");
}

</style>
