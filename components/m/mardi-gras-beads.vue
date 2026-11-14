<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zavggqbss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:mardi-gras-beads" /></template>
<style>
.zavggqbss {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 7q0-2.5 2.5-2.5q1.036 0 1.768.732T6.75 7q0 .781-.416 1.389q.916.597.916 2.111q0 .471-.089.853q1.589.404 1.589 2.397q1.841 0 2.326 1.356Q11.485 15 12 15q.486 0 .905.161q.467-1.411 2.345-1.411q0-1.993 1.589-2.397q-.089-.382-.089-.853q0-1.428.815-2.04q-.315-.572-.315-1.46q0-2.5 2.5-2.5q1.036 0 1.768.732T22.25 7t-.732 1.768q-.078.077-.158.146q.39.598.39 1.586q0 1.993-1.589 2.397q.089.382.089.853q0 2.5-2.5 2.5q0 2.5-2.5 2.5q-.568 0-1.007-.129q-.177.348-.475.647Q13.036 20 12 20q-1.841 0-2.326-1.356q-.409.106-.924.106q-1.25 0-1.875-.625T6.25 16.25q-2.5 0-2.5-2.5q0-.471.089-.853Q2.25 12.493 2.25 10.5q0-.888.315-1.46Q1.75 8.428 1.75 7");
}

</style>
