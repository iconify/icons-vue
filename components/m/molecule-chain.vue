<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r9mroebob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:molecule-chain" /></template>
<style>
.r9mroebob {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.5 6.25Q6.75 6.25 6.75 9q0 1.026.383 1.669l-1.454 1.745q-.508-.164-1.179-.164q-2.75 0-2.75 2.75t2.75 2.75T7.25 15q0-1.026-.383-1.669l1.454-1.745q.508.164 1.179.164t1.179-.164l1.454 1.745q-.383.643-.383 1.669q0 2.75 2.75 2.75T17.25 15q0-1.026-.383-1.669l1.454-1.745q.508.164 1.179.164q2.75 0 2.75-2.75T19.5 6.25T16.75 9q0 1.026.383 1.669l-1.454 1.745q-.508-.164-1.179-.164t-1.179.164l-1.454-1.745q.383-.643.383-1.669q0-2.75-2.75-2.75");
}

</style>
