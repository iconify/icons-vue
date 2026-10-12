<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="kvm_1hbrh"/><path class="cowmfabmw"/><path class="i780oo3eq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:privacy" /></template>
<style>
.cowmfabmw {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 11.75C8.9 10 10.3 9 12 9s3.1 1 4 2.75c-.9 1.75-2.3 2.75-4 2.75s-3.1-1-4-2.75");
}

.i780oo3eq {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 11.75h.01");
}

.kvm_1hbrh {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 2.75l6.6 2.45a1 1 0 0 1 .65.94v5.26c0 4.4-2.9 7.6-7.25 9.85C7.65 19 4.75 15.8 4.75 11.4V6.14a1 1 0 0 1 .65-.94Z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
