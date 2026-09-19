<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="wv2flf2hg"/><circle class="cj71dkbis"/><circle class="a_xgo4bwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nextcloud" /></template>
<style>
.a_xgo4bwr {
  cx: 38.47px;
  cy: 24px;
  r: 5.03px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.cj71dkbis {
  cx: 9.53px;
  cy: 24px;
  r: 5.03px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.wv2flf2hg {
  cx: 24px;
  cy: 24px;
  r: 9.44px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
