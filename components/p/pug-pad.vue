<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="w-xb4ib5y"/><path class="h_mdq4m_x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pug-pad" /></template>
<style>
.h_mdq4m_x {
  d: path("M13.458 6.504h21.083v3.647H13.458zm0 20.829L23.8 43.5l10.742-16.139zm7.673 11.535l5.357.045");
}

.w-xb4ib5y {
  d: path("M13.458 4.5h21.083v22.847H13.458z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
