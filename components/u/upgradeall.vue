<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rjti1kztj"/><path class="jbao-2bhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:upgradeall" /></template>
<style>
.jbao-2bhv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m42.33 6.914l-.451 5.37l-5.371-.451");
}

.rjti1kztj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.187 41.878q.471-.325.923-.673m-6.478 3.409a22 22 0 0 0 2.754-1.106M22.19 45.592a21.3 21.3 0 0 0 5.254-.205m-15.949-3.739a21.6 21.6 0 0 0 7.438 3.413M41.88 12.285A21.479 21.479 0 1 0 9.146 39.704");
}

</style>
