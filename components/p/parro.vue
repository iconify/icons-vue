<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j8lp_d_-j"/><path class="xc7wdi_dm"/><circle class="b4rngnb3a"/><circle class="j5ulj3-rs"/><path class="tlbqf67yn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:parro" /></template>
<style>
.b4rngnb3a {
  cx: 18.511px;
  cy: 19.13px;
  r: 6.109px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.j5ulj3-rs {
  cx: 20.221px;
  cy: 19.653px;
  r: 2.172px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.j8lp_d_-j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.292 5.938q-.794.089-1.563.251c-1.252.264-2.545.26-3.78-.072a106 106 0 0 1-5.09-1.526c-1.489-.485-2.822 1.067-2.134 2.473c.392.801.74 1.308.74 1.308a82 82 0 0 1-2.138-.44c-1.845-.405-2.978 1.944-1.517 3.14c1.05.86 2.129 1.648 3.07 2.3a17.34 17.34 0 0 0-3.067 8.19a17.52 17.52 0 0 0 4.866 14.057c.648.667.906 1.627.697 2.532c-.331 1.435-.764 2.777-1.332 3.811c-.405.737.216 1.613 1.053 1.533c5.453-.52 11.975-2.775 15.46-7.7V23.396h14.3c0-10.36-8.968-18.627-19.565-17.459Z");
}

.tlbqf67yn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.557 23.397V6.132");
}

.xc7wdi_dm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.557 26.238c3.198.892 7.712.838 7.712.838c-.649 3.811-4.098 7.22-7.712 8.718");
}

</style>
