<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x4rlqfbiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:send-horizontal" /></template>
<style>
.x4rlqfbiw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3.4714 2.12L22 12L3.4714 21.88C2.7309 22.2749 1.8627 21.637 2.0182 20.8123L3.575 12.5559C3.6443 12.1885 3.6443 11.8115 3.575 11.4441L2.0182 3.1877C1.8627 2.363 2.7309 1.7251 3.4714 2.12ZM3.6799 12L22 12");
}

</style>
