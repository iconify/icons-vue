<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="rhvdvboaq"/><g class="fbp0m0b1e"><circle class="bcm88nrrq"/><circle class="l1dg31bxl"/><path class="v50fjvbma"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:upside-down-face" /></template>
<style>
.bcm88nrrq {
  cx: 43.5px;
  cy: 37.4px;
  r: 5px;
}

.fbp0m0b1e {
  fill: var(--svg-color--664e27, #664e27);
}

.l1dg31bxl {
  cx: 20.5px;
  cy: 37.4px;
  r: 5px;
}

.rhvdvboaq {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--ffdd67, #ffdd67);
}

.v50fjvbma {
  d: path("M19.4 23.7c8.1-5.7 17.1-5.6 25.2 0c1 .7 1.8-.5 1.2-1.6c-2.5-4-7.4-7.6-13.8-7.6s-11.3 3.6-13.8 7.6c-.6 1.1.2 2.3 1.2 1.6");
}

</style>
