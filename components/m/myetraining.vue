<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g0u6-cb1w"/><path class="bpnxyxnsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:myetraining" /></template>
<style>
.bpnxyxnsj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m8.922 21.399l32.35.03l-2.195 5.286l-32.416.116z");
}

.g0u6-cb1w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m39.077 26.715l-2.195 5.279l-32.418.123l2.197-5.285m2.261-5.433l2.19-5.282l32.352.03l-2.192 5.283");
}

</style>
