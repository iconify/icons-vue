<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b2a-40o1j"/><path class="ygjsmucha"/><circle class="lm5r16vkk"/><circle class="uowi55blm"/><path class="t_dz1ab6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:saison-card" /></template>
<style>
.b2a-40o1j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 11.5h39v25h-39zm0 12.5h39");
}

.lm5r16vkk {
  cx: 31.605px;
  cy: 17.5px;
  r: 1px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.t_dz1ab6g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.329 19.843c.368.479.83.657 1.471.657h.888c.827 0 1.497-.67 1.497-1.5s-.67-1.5-1.497-1.5h-.98a1.501 1.501 0 0 1 .003-3h.884c.642 0 1.103.179 1.471.658M19.79 14.5v6m-3.078-1.988h-2.658m-.659 1.988l1.988-6l1.987 6m-10.251-.657c.368.479.83.657 1.47.657h.89c.826 0 1.496-.67 1.496-1.5s-.67-1.5-1.497-1.5h-.98a1.501 1.501 0 0 1 .003-3h.884c.642 0 1.103.179 1.471.658");
}

.uowi55blm {
  cx: 31.605px;
  cy: 17.5px;
  r: 3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ygjsmucha {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.605 33v-6h1.35a2.625 2.625 0 0 1 2.625 2.625v.75A2.625 2.625 0 0 1 32.955 33zm-6.395 0v-6h1.964c1.11 0 2.011.902 2.011 2.015s-.9 2.015-2.01 2.015H25.21m1.965.001l1.965 1.968m-7.008-1.986h-2.659M18.815 33l1.988-6l1.987 6m-6.395-2.012v.025a1.988 1.988 0 0 1-3.975 0v-2.025a1.988 1.988 0 1 1 3.975 0v.024m20.63-8.512v-6l3.975 6v-6");
}

</style>
