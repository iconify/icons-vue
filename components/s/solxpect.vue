<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gue12011h"/><ellipse class="llulltsor"/><path class="k2v89nbhv"/><path class="tca4m8bpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:solxpect" /></template>
<style>
.gue12011h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m19.78 29.14l-8.44.715l5.84 10.662l8.44-.717zm18.157-2.665l-4.192-1.997l2.19-2.186zm-7.915 3.112l-1.549-4.37h3.098zm-8.036-3.112l2-4.183l2.191 2.186zm.124-15.644l4.192 1.998l-2.19 2.186zm15.717 0l-2.001 4.184l-2.19-2.186zm3.109 7.823l-4.379 1.545v-3.092zm-22.126 0l4.379-1.546V20.2zm11.097-11.17l1.549 4.37h-3.098z");
}

.k2v89nbhv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m28.22 28.423l-8.44.716l5.84 10.662l8.44-.716zm-14.28-9.945l-8.44.716l5.84 10.661l8.44-.716z");
}

.llulltsor {
  cx: 29.878px;
  cy: 18.534px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 5.397px;
  ry: 5.386px;
}

.tca4m8bpv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m26.083 24.518l2.136 3.908l-8.435.708l-5.845-10.66l7.029-.587h.012m4.915 6.299l-2.701-4.926m7.317 8.955l6.188-.564L42.5 38.367l-8.435.72l-5.846-10.661l1.351-.122");
}

</style>
