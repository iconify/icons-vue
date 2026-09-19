<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><circle class="ah2wejbdv"/><path class="xzv0xqb9s"/></g><path class="btdvwwf-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tabletkiua" /></template>
<style>
.ah2wejbdv {
  cx: 31.184px;
  cy: 24px;
  r: 12.316px;
}

.btdvwwf-k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.005 34.002c-4.813 3.468-11.567 3.037-15.898-1.294c-4.81-4.81-4.81-12.607 0-17.417c4.331-4.33 11.085-4.762 15.899-1.293m-4.927 12.265L8.106 15.29");
}

.xzv0xqb9s {
  d: path("M31.184 36.316V11.684");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
