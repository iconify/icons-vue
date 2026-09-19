<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="wid0zineq"/><path class="xb-2mibar"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:svitlo" /></template>
<style>
.wid0zineq {
  d: path("M23.936 5.5c-.928.013-16.257 12.656-17.67 14.345c-1.765 2.107.383 2.742 2.13 2.559l3.626.006l-3.472.012v17.373a2.7 2.7 0 0 0 2.705 2.705h25.508a2.7 2.7 0 0 0 2.705-2.705V22.488c.618.085 3.243.338 2.893-1.526c-.054-1.114-1.102-1.624-2.796-3.003c-.299-.243-.132-3.356-.227-5.594c-.134-3.149-.581-2.071-3.326-2.207c-1.884-.093-1.095 1.784-1.147 3.55c.422 1.395-9.213-8.231-10.93-8.208Z");
}

.xb-2mibar {
  d: path("M27.96 25.119h5.386v10.973H27.96z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
