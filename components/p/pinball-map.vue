<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="u0a31d3nc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pinball-map" /></template>
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

.u0a31d3nc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.322 29.005c1.489 1.172 3.478-2.047 5.074-1.228s2.128 4.583 6.424 4.624s10.394-8.02 11.704-6.302s-1.058 16.297-17.04 16.297c-10 0-15.83-7.311-17.716-14.513c-1.842-7.033.823-13.965 4.42-13.817c2.987.123-1.337 8.268 7.133 14.938m-.606-22.131c.775-.188 3.253-.962 2.72 1.678s-3.539 1.943-3.989.961s-.164-2.291 1.269-2.639m10.005-.389c1.511.091 8.675 1.903 9.146 6.2s-5.615 2.832-8.553.839c-2.864-1.944-4.87-4.195-4.235-5.545s1.944-1.596 3.642-1.494");
}

</style>
