<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="q1m15dbht"/><path class="x_jwp_bge"/><path class="a0gtrrbuj"/><path class="pw_kz6bsy"/><path class="p4-7k1g6n"/><path class="d8lofwkuy"/><path class="u1v9jlb8h"/><path class="y13kl3xsl"/><path class="x3--vlb7d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sun-2-line-duotone" /></template>
<style>
.a0gtrrbuj {
  d: path("M12 20V22");
}

.d8lofwkuy {
  d: path("M19.7773 4.22217L17.5553 6.25375");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p4-7k1g6n {
  d: path("M22 12L20 12");
}

.pw_kz6bsy {
  d: path("M4 12L2 12");
}

.q1m15dbht {
  cx: 12px;
  cy: 12px;
  r: 5px;
}

.u1v9jlb8h {
  d: path("M4.22266 4.22217L6.44467 6.25375");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.x_jwp_bge {
  d: path("M12 2V4");
}

.x3--vlb7d {
  d: path("M19.7773 19.7778L17.5553 17.5555");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.y13kl3xsl {
  d: path("M6.44531 17.5557L4.22309 19.7779");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
