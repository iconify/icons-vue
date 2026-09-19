<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q-ud2hbxk"/><circle class="doxlmbcnu"/><path class="nyp6_ervs"/><rect class="vg-w5cb_k"/><path class="g8j7ojbgw"/><g class="y9tr6bcfx"><circle class="s0bk5ua8j"/><circle class="m7xynb9kc"/><circle class="hp65ylb_c"/></g><g class="y9tr6bcfx"><circle class="sgwlylh3a"/><circle class="u_y0dfunp"/><circle class="ion8i6bpf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:muttiapp" /></template>
<style>
.doxlmbcnu {
  cx: 36.557px;
  cy: 20.203px;
  r: 0.75px;
  fill: currentColor;
}

.g8j7ojbgw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.579 9.719h30.686M8.444 9.712H6.942a1.13 1.13 0 0 0-1.13 1.13v7.914c0 .547.444.99.992.99h1.608M39.556 9.712h1.502c.624 0 1.13.506 1.13 1.13v7.914a.99.99 0 0 1-.992.99h-1.609M8.508 33.028h10.019m.069-.006c5.027-.547 2.005-3.068 8.643-2.95m-.583.006h12.812");
}

.hp65ylb_c {
  cx: 17.433px;
  cy: 38.997px;
  r: 1.061px;
}

.ion8i6bpf {
  cx: 30.598px;
  cy: 38.997px;
  r: 1.061px;
}

.m7xynb9kc {
  cx: 14.734px;
  cy: 38.125px;
  r: 1.301px;
}

.nyp6_ervs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.557 22.619v5.436");
}

.q-ud2hbxk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.675 22.602v3.321a2.02 2.02 0 0 0 2.013 2.014h0a2.02 2.02 0 0 0 2.013-2.014v-3.321m0 3.422v2.013m3.085-7.099v6.04c0 .604.402 1.006 1.006 1.006h.302m-2.416-5.435h2.215m3.117-1.622v6.04c0 .604.402 1.007 1.006 1.007h.302m-2.416-5.436h2.215m-22.876 5.359v-7.952l4.027 8.053l4.026-8.053v8.053");
}

.s0bk5ua8j {
  cx: 12.023px;
  cy: 36.495px;
  r: 1.613px;
}

.sgwlylh3a {
  cx: 36.007px;
  cy: 36.495px;
  r: 1.613px;
}

.u_y0dfunp {
  cx: 33.296px;
  cy: 38.124px;
  r: 1.301px;
}

.vg-w5cb_k {
  width: 31.079px;
  height: 38px;
  x: 8.461px;
  y: 5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.936px;
  ry: 2.936px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
