<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k1zhx6bhg"/><path class="f-73vxl9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:roblox" /></template>
<style>
.f-73vxl9v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m29.32 20.51l-8.182-2.192a.513.513 0 0 0-.628.363l-2.192 8.18a.513.513 0 0 0 .363.63l8.18 2.191a.513.513 0 0 0 .63-.363l2.191-8.18a.513.513 0 0 0-.363-.629");
}

.k1zhx6bhg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.265 12.672L14.712 5.557a1.666 1.666 0 0 0-2.04 1.178L5.557 33.288a1.666 1.666 0 0 0 1.178 2.04l26.553 7.114a1.666 1.666 0 0 0 2.04-1.178l7.114-26.552a1.666 1.666 0 0 0-1.178-2.04Z");
}

</style>
