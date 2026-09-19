<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><g class="y9tr6bcfx"><circle class="pzkm1rb7v"/><path class="ufwizigbc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:moshidon" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.pzkm1rb7v {
  cx: 35.157px;
  cy: 25.74px;
  r: 4.993px;
}

.ufwizigbc {
  d: path("M17.917 26.765v-6.464a5.034 5.034 0 0 0-5.034-5.034h0A5.034 5.034 0 0 0 7.849 20.3v10.432M17.917 20.3a5.034 5.034 0 0 1 5.033-5.033h0a5.034 5.034 0 0 1 5.034 5.034h0v10.432");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
