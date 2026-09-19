<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="rhvdvboaq"/><g class="n1mjunbsu"><circle class="ak9anbb-l"/><circle class="vc35oqboj"/></g><g class="l7rgeptfg"><path class="cv4eqerwu"/><path class="h_b2x7too"/></g><g class="fbp0m0b1e"><ellipse class="flpqd7ari"/><ellipse class="dtz1dgbka"/><path class="xz1m3q2dk"/></g><path class="e-imofbet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:nerd-face" /></template>
<style>
.ak9anbb-l {
  cx: 17px;
  cy: 30px;
  r: 11px;
}

.cv4eqerwu {
  d: path("M36 27c-1.8-1.3-6.2-1.3-8 0c-1.1-1-.9-2.1-2-3.1c3.1-2.3 8.4-2.7 12 0c-1.1 1-.9 2.1-2 3.1");
}

.dtz1dgbka {
  cx: 44px;
  cy: 30.5px;
  rx: 4px;
  ry: 5px;
}

.e-imofbet {
  fill: var(--svg-color--917524, #917524);
  d: path("M53.2 15.7c-3.2-2.7-7.5-3.9-11.7-3.1c-.6.1-1.1-2-.4-2.2c4.8-.9 9.8.5 13.5 3.6c.6.5-1 2.1-1.4 1.7m-30.7-3.3c-4.2-.7-8.5.4-11.7 3.1c-.4.4-2-1.2-1.4-1.7c3.7-3.2 8.7-4.5 13.5-3.6c.7.2.2 2.3-.4 2.2");
}

.fbp0m0b1e {
  fill: var(--svg-color--664e27, #664e27);
}

.flpqd7ari {
  cx: 20px;
  cy: 30.5px;
  rx: 4px;
  ry: 5px;
}

.h_b2x7too {
  d: path("M47 17c-7.2 0-13 5.8-13 13s5.8 13 13 13s13-5.8 13-13s-5.8-13-13-13m0 23c-5.5 0-10-4.5-10-10s4.5-10 10-10s10 4.5 10 10s-4.5 10-10 10M17 17C9.8 17 4 22.8 4 30s5.8 13 13 13s13-5.8 13-13s-5.8-13-13-13m0 23c-5.5 0-10-4.5-10-10s4.5-10 10-10s10 4.5 10 10s-4.5 10-10 10");
}

.l7rgeptfg {
  fill: var(--svg-color--494949, #494949);
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.rhvdvboaq {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--ffdd67, #ffdd67);
}

.vc35oqboj {
  cx: 47px;
  cy: 30px;
  r: 11px;
}

.xz1m3q2dk {
  d: path("M26.7 51.3c5.8 1.5 12 .4 16.9-3c1.2-.9-1.1-4-2.3-3.2c-3.2 2.3-8.4 3.8-13.7 2.4c-1.3-.3-2.4 3.4-.9 3.8");
}

</style>
