<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="q82j_2vrq"/><path class="cdlrdrbee"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:send-horizontal-two-tone" /></template>
<style>
.cdlrdrbee {
  d: path("M3.4714 2.12L22 12L3.4714 21.88C2.7309 22.2749 1.8627 21.637 2.0182 20.8123L3.575 12.5559C3.6443 12.1885 3.6443 11.8115 3.575 11.4441L2.0182 3.1877C1.8627 2.363 2.7309 1.7251 3.4714 2.12ZM3.6799 12L22 12");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q82j_2vrq {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3.9419 1.2376L22.4705 11.1176C22.7964 11.2914 23 11.6307 23 12C23 12.3693 22.7964 12.7086 22.4705 12.8824L3.9419 22.7624C3.6523 22.9169 3.3291 22.9976 3.0009 22.9976C1.8963 22.9976 1.0009 22.1022 1.0009 20.9976C1.0009 20.8733 1.0125 20.7492 1.0355 20.627L2.5924 12.3706C2.6154 12.2484 2.627 12.1243 2.627 12C2.627 11.8757 2.6154 11.7516 2.5924 11.6294L1.0355 3.373C1.0125 3.2508 1.0009 3.1267 1.0009 3.0024C1.0009 1.8978 1.8963 1.0024 3.0009 1.0024C3.3291 1.0024 3.6523 1.0831 3.9419 1.2376Z");
  stroke: none;
}

</style>
