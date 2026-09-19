<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="rhvdvboaq"/><g class="fbp0m0b1e"><circle class="ngs-uid3z"/><circle class="pexrgrbpp"/><path class="esq-w_bfk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:slightly-frowning-face" /></template>
<style>
.esq-w_bfk {
  d: path("M23 47.6c5.8-4.8 12.2-4.8 18 0c.7.6 1.3-.4.8-1.3c-1.8-3.4-5.3-6.5-9.8-6.5s-8.1 3.1-9.8 6.5c-.5.9.1 1.9.8 1.3");
}

.fbp0m0b1e {
  fill: var(--svg-color--664e27, #664e27);
}

.ngs-uid3z {
  cx: 20.5px;
  cy: 26.6px;
  r: 5px;
}

.pexrgrbpp {
  cx: 43.5px;
  cy: 26.6px;
  r: 5px;
}

.rhvdvboaq {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--ffdd67, #ffdd67);
}

</style>
