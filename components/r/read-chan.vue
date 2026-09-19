<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="spn25qyqo"/><path class="hp6u21bsg"/><path class="j8iygtb2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:read-chan" /></template>
<style>
.hp6u21bsg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m39.693 18.353l1.384-3.09l-4.818-4.806l-2.694-.025l-9.527 13.507l15.868 4.29l1.954-1.565l.806-6.914z");
}

.j8iygtb2t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m29.508 39.533l3.083 1.399l4.828-4.797l.037-2.694l-13.418-9.503l-4.408 15.764l1.556 1.96l6.911.838zM8.31 29.469L6.928 32.56l4.823 4.8l2.694.024l9.593-13.446l-15.953-4.345l-1.952 1.566l-.8 6.916z");
}

.spn25qyqo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.442 8.488L15.34 7.132l-4.76 4.863v2.695l13.459 9.248L28.315 8.18l-1.583-1.94l-6.922-.74z");
}

</style>
