<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bn6ebpb5p"/><circle class="dr36jwb_v"/><circle class="k3jqu1vln"/><circle class="t6wz8cb3t"/><circle class="a8opedcca"/><circle class="k0evexoqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-casino" /></template>
<style>
.a8opedcca {
  cx: 16.5px;
  cy: 16.5px;
  r: 1.5px;
  fill: currentColor;
}

.bn6ebpb5p {
  fill: currentColor;
  d: path("M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2m0 16H5V5h14z");
}

.dr36jwb_v {
  cx: 7.5px;
  cy: 16.5px;
  r: 1.5px;
  fill: currentColor;
}

.k0evexoqr {
  cx: 16.5px;
  cy: 7.5px;
  r: 1.5px;
  fill: currentColor;
}

.k3jqu1vln {
  cx: 7.5px;
  cy: 7.5px;
  r: 1.5px;
  fill: currentColor;
}

.t6wz8cb3t {
  cx: 12px;
  cy: 12px;
  r: 1.5px;
  fill: currentColor;
}

</style>
