<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w25elbcmn"/><path class="bn6ebpb5p"/><circle class="dr36jwb_v"/><circle class="k3jqu1vln"/><circle class="t6wz8cb3t"/><circle class="a8opedcca"/><circle class="k0evexoqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-casino" /></template>
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

.w25elbcmn {
  fill: currentColor;
  d: path("M5 19h14V5H5zM16.5 6c.83 0 1.5.67 1.5 1.5S17.33 9 16.5 9S15 8.33 15 7.5S15.67 6 16.5 6m0 9c.83 0 1.5.67 1.5 1.5s-.67 1.5-1.5 1.5s-1.5-.67-1.5-1.5s.67-1.5 1.5-1.5M12 10.5c.83 0 1.5.67 1.5 1.5s-.67 1.5-1.5 1.5s-1.5-.67-1.5-1.5s.67-1.5 1.5-1.5M7.5 6C8.33 6 9 6.67 9 7.5S8.33 9 7.5 9S6 8.33 6 7.5S6.67 6 7.5 6m0 9c.83 0 1.5.67 1.5 1.5S8.33 18 7.5 18S6 17.33 6 16.5S6.67 15 7.5 15");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
