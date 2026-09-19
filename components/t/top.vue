<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="pnznvabui"/><circle class="cm1idbc4z"/><path class="t_4ywfq7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:top" /></template>
<style>
.cm1idbc4z {
  cx: 24px;
  cy: 24px;
  r: 5.499px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.pnznvabui {
  cx: 24px;
  cy: 24px;
  r: 12.498px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.t_4ywfq7f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.498 5.5H24a18.502 18.502 0 0 0-13.08 31.581a18.495 18.495 0 0 0 31.577-13.08z");
}

</style>
