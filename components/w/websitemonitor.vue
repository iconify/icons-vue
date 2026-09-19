<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jnqhqcbtz"/><circle class="a3i434bwt"/><path class="jngq_5bnr"/><circle class="vqogbbbht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:websitemonitor" /></template>
<style>
.a3i434bwt {
  cx: 24px;
  cy: 24px;
  r: 5.625px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.jngq_5bnr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 18.375A12.94 12.94 0 0 0 13.5 24A12.94 12.94 0 0 0 24 29.625A12.94 12.94 0 0 0 34.5 24A12.94 12.94 0 0 0 24 18.375");
}

.jnqhqcbtz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.226 25.999A16 16 0 0 0 39.37 24a16 16 0 0 0-.143-1.999l4.335-3.393a1.02 1.02 0 0 0 .246-1.312l-4.1-7.103a1.014 1.014 0 0 0-1.25-.44l-5.105 2.06a15.6 15.6 0 0 0-3.464-2.02l-.769-5.432a1.054 1.054 0 0 0-1.025-.861h-8.2a1.035 1.035 0 0 0-1.015.861l-.768 5.433a15.2 15.2 0 0 0-3.465 2.019l-5.104-2.06a1.025 1.025 0 0 0-1.251.44l-4.1 7.104a1.03 1.03 0 0 0 .246 1.312l4.326 3.393A16 16 0 0 0 8.62 24a16 16 0 0 0 .144 1.999l-4.326 3.393a1.02 1.02 0 0 0-.246 1.312l4.1 7.103a1.014 1.014 0 0 0 1.25.44l5.105-2.06a15.6 15.6 0 0 0 3.464 2.02l.769 5.432a1.035 1.035 0 0 0 1.015.861h8.2a1.035 1.035 0 0 0 1.015-.861l.768-5.432a15.2 15.2 0 0 0 3.465-2.02l5.104 2.06a1.025 1.025 0 0 0 1.25-.44l4.1-7.104a1.03 1.03 0 0 0-.246-1.312Z");
}

.vqogbbbht {
  cx: 24px;
  cy: 24px;
  r: 0.75px;
  fill: currentColor;
}

</style>
