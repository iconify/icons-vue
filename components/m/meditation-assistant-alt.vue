<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="y6xelfb3e"/><path class="jfrwt_9qa"/><path class="g167wsc-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:meditation-assistant-alt" /></template>
<style>
.g167wsc-h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 41.44c6.79 0 14.38-2.17 16.79-3.397c1.423-.726 1.573-.959 1.654-2.43c.134-2.471-.015-3.653-.015-7.513c0 0-5.696.593-9.106-5.689c-.791-1.457-2.892-5.38-9.323-5.38s-8.532 3.923-9.323 5.38c-3.41 6.282-9.106 5.69-9.106 5.69c0 3.859-.15 5.04-.015 7.512c.08 1.471.23 1.704 1.655 2.43C9.619 39.27 17.21 41.44 24 41.44");
}

.jfrwt_9qa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.315 28.28c-1.284 1.353-2.13 2.384-7.653 3.68h7.653zm17.37 0c1.284 1.353 2.13 2.384 7.653 3.68h-7.653z");
}

.y6xelfb3e {
  cx: 24px;
  cy: 10.592px;
  r: 4.032px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
