<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="rhvdvboaq"/><g class="fbp0m0b1e"><circle class="ry06sibgd"/><circle class="xrvu5hbnt"/><path class="hkcofhbjo"/></g><path class="nan_bnbrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:smiling-face-with-open-mouth" /></template>
<style>
.fbp0m0b1e {
  fill: var(--svg-color--664e27, #664e27);
}

.hkcofhbjo {
  d: path("M49 38c0-.8-.5-1.8-1.8-2.1c-3.5-.7-8.6-1.3-15.2-1.3s-11.7.7-15.2 1.3c-1.3.3-1.8 1.3-1.8 2.1c0 7.3 5.6 14.6 17 14.6S49 45.3 49 38");
}

.nan_bnbrt {
  fill: var(--svg-color--fff, #fff);
  d: path("M44.7 38.3c-2.2-.4-6.8-1-12.7-1s-10.5.6-12.7 1c-1.3.2-1.4.7-1.3 1.5c.1.4.1 1 .3 1.6c.1.6.3.9 1.3.8c1.9-.2 23-.2 24.9 0c1 .1 1.1-.2 1.3-.8c.1-.6.2-1.1.3-1.6c0-.8-.1-1.3-1.4-1.5");
}

.rhvdvboaq {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--ffdd67, #ffdd67);
}

.ry06sibgd {
  cx: 20.5px;
  cy: 24.5px;
  r: 5px;
}

.xrvu5hbnt {
  cx: 43.5px;
  cy: 24.5px;
  r: 5px;
}

</style>
