<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="y24ur3btk"/><path class="s4ksflbzu"/><circle class="k_q5jgycv"/><circle class="f0rf3qb6m"/><circle class="jhjehzb4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:smytten" /></template>
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

.f0rf3qb6m {
  cx: 29px;
  cy: 34px;
  r: 1.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.jhjehzb4q {
  cx: 19px;
  cy: 34px;
  r: 1.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.k_q5jgycv {
  cx: 24px;
  cy: 34px;
  r: 1.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.s4ksflbzu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.813 21.203v2.907c0 .973-.796 1.762-1.778 1.762s-1.779-.789-1.779-1.762v-2.907m-8.564 1.762c0-.973.796-1.762 1.779-1.762s1.778.789 1.778 1.762v2.907m-3.557-4.669v4.669m3.557-2.907c0-.973.796-1.762 1.779-1.762s1.778.789 1.778 1.762v2.907m-11.601-.394c.324.27.675.394 1.462.394h.4c.649 0 1.175-.523 1.175-1.167s-.526-1.167-1.176-1.167h-.798c-.65 0-1.175-.523-1.175-1.168s.526-1.167 1.175-1.167h.4c.787 0 1.137.124 1.462.394m16.067-1.847v5.242c0 .486.398.88.89.88h.266m-2.09-4.669h1.868m2.606-1.453v5.242c0 .486.398.88.89.88h.266m-2.09-4.669h1.868m10.236 4.669v-2.907c0-.973-.796-1.762-1.778-1.762s-1.779.789-1.779 1.762m0 2.907v-4.669m-1.683 3.78c-.306.531-.884.89-1.545.89a1.77 1.77 0 0 1-1.779-1.763v-1.145c0-.973.796-1.762 1.779-1.762s1.778.79 1.778 1.762v.573h-3.557");
}

.y24ur3btk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.813 24.11v2.379a1.77 1.77 0 0 1-1.778 1.761a1.78 1.78 0 0 1-1.258-.516");
}

</style>
