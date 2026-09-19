<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jqr92vbmq"/><path class="uxcswrb5z"/><path class="cw26ksuwx"/><path class="hvgjam6pa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:simplewear" /></template>
<style>
.cw26ksuwx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m28.279 20.685l-.927 5.109a7.88 7.88 0 0 0-3.178 6.297a7.88 7.88 0 0 0 3.178 6.3l.927 5.108h7.555l.926-5.108a7.88 7.88 0 0 0 3.177-6.3a7.88 7.88 0 0 0-3.182-6.327l-.92-5.079z");
}

.hvgjam6pa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.588 32.092a5.53 5.53 0 0 1-5.527 5.533h-.005a5.53 5.53 0 0 1-5.532-5.528v-.005a5.53 5.53 0 0 1 5.528-5.532h.004a5.53 5.53 0 0 1 5.532 5.528z");
}

.jqr92vbmq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.034 43.5H13.177a5.1 5.1 0 0 1-5.114-5.086v-28.8A5.1 5.1 0 0 1 13.149 4.5h15.885a5.1 5.1 0 0 1 5.113 5.087V20.64");
}

.uxcswrb5z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.64 34.673H11.334V10.06h19.543v10.624m-12.782 18.44h6.02");
}

</style>
