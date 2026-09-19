<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k8p7ecr7k"/><path class="mypa4qp-u"/><path class="p101i_bea"/><path class="uc6bfbbvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:swarail" /></template>
<style>
.k8p7ecr7k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.676 38.702c-1.163-.422-2.23-.941-3.2-1.543s-1.843-1.285-2.618-2.035a14.8 14.8 0 0 1-3.468-5.158m-.687-8.992a15.3 15.3 0 0 1 1-2.943c3.499-7.638 12.765-10.884 20.696-7.25c1.982.908 3.78 1.983 5.252 3.539c.368.389.83.94 1.314 1.611s.993 1.46 1.454 2.324s.876 1.802 1.172 2.772m-3.313 16.555c-1.776 2.169-4.352 4.066-6.224 4.722");
}

.mypa4qp-u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.265 42.934c-12.35.895-21.072-7.516-21.072-18.282S13.178 5 24.002 5s21.81 7.675 19.493 22.863");
}

.p101i_bea {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m5.887 24.452l19.175-7.706c2.67-.612 4.583-1.5 8.712.596c4.707 4.264 8.084 9.616 9.785 14.466c.4 2.417-1.216 2.834-2.712 3.403l-6.738.559c-1.738-.362-3.557-.912-4.616-1.08l-2.122-2.048l-21.372-5.36m-.075-1.787l17.773-5.47M6.036 26.277l21.595 1.675");
}

.uc6bfbbvw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m26.626 20.618l7.148 9.195c2.942 3.221 2.319 4.733-.856 4.095M27.643 18.48l6.913 7.87h6.068");
}

</style>
