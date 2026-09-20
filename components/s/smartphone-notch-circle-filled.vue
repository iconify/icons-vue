<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGSSj06bwG"><path class="k5-vjlrin"/><path clip-rule="evenodd" class="vrji0hbye"/></mask></defs><circle mask="url(#SVGSSj06bwG)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:smartphone-notch-circle-filled" /></template>
<style>
.bd9gczbnq {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

.ft5dv1b6b {
  fill: none;
}

.k5-vjlrin {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

.vrji0hbye {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
  d: path("M9 3h9c1.105 0 2 .943 2 2.105v15.79C20 22.057 19.105 23 18 23H9c-1.105 0-2-.943-2-2.105V5.105C7 3.943 7.895 3 9 3m1 2a1 1 0 0 0-1 1v14a1 1 0 0 0 1 1h7a1 1 0 0 0 1-1V6a1 1 0 0 0-1-1h-1v1.5a.5.5 0 0 1-.5.5h-4a.5.5 0 0 1-.5-.5V5z");
}

</style>
