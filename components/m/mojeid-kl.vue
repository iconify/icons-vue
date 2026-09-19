<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="t2-xbsxyb"/><path class="g7ek2zbhx"/><circle class="mihmin-pr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mojeid-kl" /></template>
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

.g7ek2zbhx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.306 35.88V12.334h6.424c6.782 0 12.492 4.71 12.492 10.301v2.944c0 5.592-5.71 10.301-12.492 10.301z");
}

.mihmin-pr {
  cx: 12.894px;
  cy: 14.131px;
  r: 0.987px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.t2-xbsxyb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.473 20.073v15.699c5.306-10.36 12.104-15.238 21.136-15.6");
}

</style>
