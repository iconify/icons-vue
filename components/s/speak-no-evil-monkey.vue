<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<ellipse class="enl2h0ype"/><circle class="pocdjubkt"/><circle class="xyjnbub8u"/><circle class="d2oz3gwfc"/><g class="euxxm2bmm"><path class="pkh_t0fwz"/><path class="k50kao52t"/></g><path class="iv3n3ckce"/><g class="l11lztblz"><path class="n263fq0ng"/><ellipse class="d0csb0b7a"/><ellipse class="t4mkyabcp"/></g><path class="ion_j6bdp"/><path class="jilkgz0vt"/><path class="czv48gbrf"/><path class="f0-c7ebnm"/><path class="bq6-qfb0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:speak-no-evil-monkey" /></template>
<style>
.bq6-qfb0i {
  fill: var(--svg-color--ffd6bb, #ffd6bb);
  d: path("M39.6 43.7s-6.2-2.3-10.3 0c-2 1.1 9.4 4.3 9.4 4.3s-12.1-3.9-13-.8c-.8 2.9 12 5.7 12 5.7s-12.3-3.7-10.7-.5c1.8 3.4 12.2 8.9 16.8 8c6.6-1.3 9.8-7.2 1-19.4c-4.3-6.1-2.9 2.1-5.2 2.7");
}

.czv48gbrf {
  fill: var(--svg-color--89664c, #89664c);
  d: path("M48.3 50.2L59 62H45l-2.2-2.6z");
}

.d0csb0b7a {
  cx: 40.7px;
  cy: 31.7px;
  rx: 3.5px;
  ry: 4.5px;
}

.d2oz3gwfc {
  cx: 10.2px;
  cy: 33px;
  r: 5.4px;
  fill: var(--svg-color--ffc5d3, #ffc5d3);
}

.enl2h0ype {
  cx: 53.7px;
  cy: 33px;
  fill: var(--svg-color--89664c, #89664c);
  rx: 8.3px;
  ry: 8.2px;
}

.euxxm2bmm {
  fill: var(--svg-color--89664c, #89664c);
}

.f0-c7ebnm {
  fill: var(--svg-color--ddb199, #ddb199);
  d: path("M38.2 43.7s-6.2-2.3-10.3 0c-2 1.1 9.4 4.3 9.4 4.3s-12.1-3.9-13-.8c-.8 2.9 12 5.7 12 5.7s-12.3-3.7-10.7-.5c1.8 3.4 12.2 8.9 16.8 8c6.8-1.4-1.8-17.3-4.2-16.7");
}

.ion_j6bdp {
  fill: var(--svg-color--89664c, #89664c);
  d: path("M14.9 52L6.6 62h12.9l4-3.6z");
}

.iv3n3ckce {
  fill: var(--svg-color--e0ac7e, #e0ac7e);
  d: path("M52 28.2c0-16.9-20-6.1-20-6.1s-20-10.8-20 6.1c0 4.7 2.9 9 7.5 11.7c-1.3 1.7-2.1 3.6-2.1 5.7c0 6.1 6.6 11 14.7 11s14.7-4.9 14.7-11c0-2.1-.8-4-2.1-5.7c4.4-2.7 7.3-7 7.3-11.7");
}

.jilkgz0vt {
  fill: var(--svg-color--ffd6bb, #ffd6bb);
  d: path("M20.2 43.3s4.9-4.5 9.5-3.9c2.3.3-7.1 7.6-7.1 7.6s9.7-8.2 11.7-5.6c1.8 2.3-8.9 9.8-8.9 9.8s10-8.1 9.6-4.6c-.3 3.9-7.9 12.9-12.5 13.8c-6.6 1.3-11.8-2.9-8.3-17.5c1.8-7.3 3.6.8 6 .4");
}

.k50kao52t {
  d: path("M55.3 27.6C55.3 17.9 44.9 10 32 10S8.7 17.9 8.7 27.6c0 2.3.6 4.4 1.6 6.4c-1 2-1.6 4.2-1.6 6.4C8.7 50.1 19.1 58 32 58s23.3-7.9 23.3-17.6c0-2.3-.6-4.4-1.6-6.4c1-2 1.6-4.2 1.6-6.4");
}

.l11lztblz {
  fill: var(--svg-color--3b302a, #3b302a);
}

.n263fq0ng {
  d: path("M35.1 38.7c0 1.1-.4 2.1-1 2.1s-1-.9-1-2.1c0-1.1.4-2.1 1-2.1s1 1 1 2.1m-4.2 0c0 1.1-.4 2.1-1 2.1s-1-.9-1-2.1c0-1.1.4-2.1 1-2.1c.5.1 1 1 1 2.1");
}

.pkh_t0fwz {
  d: path("M43.4 10.8c1.1-.6 1.9-.9 1.9-.9c-3.2-1.1-6-1.8-8.5-2.1c1.3-1 2.1-1.3 2.1-1.3C18.5 3.6 8.8 15.5 8.8 26h46.4c-.7-7.4-4.8-12.4-11.8-15.2");
}

.pocdjubkt {
  cx: 53.7px;
  cy: 33px;
  r: 5.4px;
  fill: var(--svg-color--ffc5d3, #ffc5d3);
}

.t4mkyabcp {
  cx: 23.3px;
  cy: 31.7px;
  rx: 3.5px;
  ry: 4.5px;
}

.xyjnbub8u {
  cx: 10.2px;
  cy: 33px;
  r: 8.2px;
  fill: var(--svg-color--89664c, #89664c);
}

</style>
