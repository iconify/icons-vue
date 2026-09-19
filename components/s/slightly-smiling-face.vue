<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="rhvdvboaq"/><g class="fbp0m0b1e"><circle class="ngs-uid3z"/><circle class="pexrgrbpp"/><path class="w6h6_ubkz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:slightly-smiling-face" /></template>
<style>
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

.w6h6_ubkz {
  d: path("M44.6 40.3c-8.1 5.7-17.1 5.6-25.2 0c-1-.7-1.8.5-1.2 1.6c2.5 4 7.4 7.7 13.8 7.7s11.3-3.6 13.8-7.7c.6-1.1-.2-2.3-1.2-1.6");
}

</style>
