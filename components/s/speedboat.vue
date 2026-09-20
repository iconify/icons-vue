<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="u50s4ib0m"/><path class="pec_i-b7h"/><path class="w18c2nb2x"/><path class="e1v2q_qyd"/><path class="t8_c5g4de"/><path class="y2lp1eb9f"/><path class="cjqn5l3hu"/><path class="a_o1c_b2t"/><path class="yu0o5ab6d"/><path class="ls7efpb7k"/><path class="c1oguotfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:speedboat" /></template>
<style>
.a_o1c_b2t {
  fill: var(--svg-color--c1694f, #c1694f);
  d: path("M30 16c.97.243 0 2-1 3s-10-1-10-1l2-3s5 0 9 1");
}

.c1oguotfv {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M23 14c-.553 0-1 1.343-1 3c0 .612.062 1.181.167 1.656q.755.191 1.592.278C23.907 18.41 24 17.741 24 17c0-1.656-.447-3-1-3");
}

.cjqn5l3hu {
  fill: var(--svg-color--5c913b, #5c913b);
  d: path("M34 16h-1a2 2 0 0 0-2 2h1a1 1 0 0 1 1 1v1h1c1.104 0 2 .104 2-1s-.896-3-2-3");
}

.e1v2q_qyd {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
  d: path("M5 13c4 0 11 0 18 1s10 1 10 3v3c0 1.414-6.869.447-10 0c-7-1-14-3-18-4c-4.047-1.011-7-3 0-3");
}

.ls7efpb7k {
  fill: var(--svg-color--55acee, #55acee);
  d: path("M21 15v-1l-4 1l-2 2l4 1z");
}

.pec_i-b7h {
  fill: var(--svg-color--dd2e44, #dd2e44);
  d: path("M1 14c9.055.053 11 1 17 2c2.959.493 7 1 11 1c2 0 4 1 4 4c0 2 .534 3.187-5.433 3.815C23.59 25.233 13 23 9 21c-6-3-9-7.005-8-7");
}

.t8_c5g4de {
  fill: var(--svg-color--a0041e, #a0041e);
  d: path("M30.592 24.322c2.122-.539 2.403-1.307 2.418-2.361c-1.263.619-3.699.32-5.886.047c-7.96-.995-16.481-2.935-24.722-5.608c1.043 1.04 2.584 2.29 4.568 3.483c6.706 1.901 13.484 3.307 19.905 4.109c1.259.157 2.53.312 3.717.33");
}

.u50s4ib0m {
  fill: var(--svg-color--5c913b, #5c913b);
  d: path("M33 27h-2l1-8h2z");
}

.w18c2nb2x {
  fill: var(--svg-color--55acee, #55acee);
  d: path("M0 24h36v12H0z");
}

.y2lp1eb9f {
  fill: var(--svg-color--55acee, #55acee);
  d: path("M12 24c3-2 7-5 6-3s-1.001 3 1 2s5-2 4 0s2 1 3 0s4 0 3 1s-9 2-12 2s-5-2-5-2");
}

.yu0o5ab6d {
  fill: var(--svg-color--a0041e, #a0041e);
  d: path("M29 19c.328-.328.645-.737.899-1.147c-1.475-.764-3.63-1.385-6.079-1.664a22 22 0 0 0-3.527-.128L19 18s9 2 10 1");
}

</style>
