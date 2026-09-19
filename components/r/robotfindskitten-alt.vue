<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nuu5_2bmg"/><g class="y9tr6bcfx"><circle class="rrnqh53gc"/><circle class="h5bv8mrnq"/><circle class="u4vd61z-f"/><circle class="dsdxprb7h"/><path class="q1ne59bil"/></g><path class="v7ajb8ucc"/><circle class="rp1ljg7zm"/><circle class="fc6p2ibjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:robotfindskitten-alt" /></template>
<style>
.dsdxprb7h {
  cx: 34.069px;
  cy: 24.795px;
  r: 1.02px;
}

.fc6p2ibjt {
  cx: 12.608px;
  cy: 30.615px;
  r: 0.75px;
  fill: currentColor;
}

.h5bv8mrnq {
  cx: 7.559px;
  cy: 21.23px;
  r: 1.02px;
}

.nuu5_2bmg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.83 21.358a1.386 1.386 0 0 0-1.076 2.26l2.222 2.609l2.2-2.583l.01-.012l.012-.014a1.387 1.387 0 1 0-2.222-1.653a1.38 1.38 0 0 0-1.145-.607zm-12.722-3.897c3.095 0 5.604 2.475 5.604 5.528v.79H4.505v-.79c0-3.053 2.509-5.528 5.604-5.528zm-4.839-.826l1.592 1.849m8.086-1.849l-1.592 1.849");
}

.q1ne59bil {
  d: path("m31.01 16.638l4.078 5.098h3.06l4.077-5.098v14.275H31.01z");
}

.rp1ljg7zm {
  cx: 7.608px;
  cy: 30.615px;
  r: 0.75px;
  fill: currentColor;
}

.rrnqh53gc {
  cx: 12.657px;
  cy: 21.23px;
  r: 1.02px;
}

.u4vd61z-f {
  cx: 39.167px;
  cy: 24.795px;
  r: 1.02px;
}

.v7ajb8ucc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.735 28.873h2.549m-2.549-1.529h2.549m8.667 1.529H43.5m-2.549-1.529H43.5m-6.882 1.019v-1.332m0 1.332l-.805.998m-.361-1.73l1.166.732m0 0l.804.998m.361-1.73l-1.165.732M4.5 23.774h11.216v5.608H4.5z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
