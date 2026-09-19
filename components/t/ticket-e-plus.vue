<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k_rcriaem"/><path class="c67iqbc2x"/><path class="g4qxnp04f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ticket-e-plus" /></template>
<style>
.c67iqbc2x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.022 20.996a2.5 4.5 25 0 1-4.168 3.022a2.5 4.5 25 0 1-.364-5.135a2.5 4.5 25 0 1 4.168-3.022a2.5 4.5 25 0 1 .364 5.135");
}

.g4qxnp04f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.282 20.373a1.5 1.75 25 0 1-2.099.952a1.5 1.75 25 0 1-.62-2.22a1.5 1.75 25 0 1 2.1-.952a1.5 1.75 25 0 1 .619 2.22M34 17.5h9.5m-3.925-4.678l-1.65 9.356");
}

.k_rcriaem {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.084 34.923c-5.403 2.52-16.603 2.936-19.814-3.95c-2.684-5.756 1.835-13.544 10.094-17.395c8.259-3.852 15.259-1.885 16.814 1.449c3.698 7.93-9.528 13.486-13.594 12.396c-1.39-.373-1.642 2.258 2.25 2.258c3.946 0 6.49-4.07 9.291-2.452c2.402 1.387 1.309 5.085-5.04 7.694z");
}

</style>
