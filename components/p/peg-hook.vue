<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kv73ebu1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:peg-hook" /></template>
<style>
.kv73ebu1i {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.25 3.75h.5q2.5 0 2.5 2.5v2h11.89l1.774-2.219q.046-.057.103-.105t.121-.083t.135-.058t.144-.03q.074-.009.147-.002q.074.006.145.027t.136.054t.124.08t.105.103t.083.121t.058.135t.03.144t.002.147t-.027.145t-.054.136q-.034.066-.08.124l-2 2.5q-.053.065-.119.118t-.142.089q-.076.037-.158.055q-.083.019-.167.019h-5.723L7.25 15.345v2.405q0 2.5-2.5 2.5h-.5q-2.5 0-2.5-2.5V6.25q0-2.5 2.5-2.5m3 9.619l4.223-3.619H7.25z");
}

</style>
