<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<ellipse class="enl2h0ype"/><circle class="pocdjubkt"/><circle class="xyjnbub8u"/><circle class="d2oz3gwfc"/><g class="euxxm2bmm"><path class="pkh_t0fwz"/><path class="k50kao52t"/></g><path class="iv3n3ckce"/><g class="l11lztblz"><path class="f3y311b3q"/><ellipse class="d0csb0b7a"/><ellipse class="t4mkyabcp"/><path class="agc7lfb-f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:monkey-face" /></template>
<style>
.agc7lfb-f {
  d: path("M41.8 44.5c1.4 1.2-2.9 6.9-9.8 7c-6.9 0-11.3-5.8-9.8-7c.4-.3 5.2.9 9.8.9c4.7 0 9.5-1.2 9.8-.9");
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

.f3y311b3q {
  d: path("M35.1 38.7c0 1.1-.4 2.1-1 2.1s-1-.9-1-2.1c0-1.1.4-2.1 1-2.1c.6.1 1 1 1 2.1m-4.2 0c0 1.1-.4 2.1-1 2.1s-1-.9-1-2.1c0-1.1.4-2.1 1-2.1c.5.1 1 1 1 2.1");
}

.iv3n3ckce {
  fill: var(--svg-color--e0ac7e, #e0ac7e);
  d: path("M52 28.2c0-16.9-20-6.1-20-6.1s-20-10.8-20 6.1c0 4.7 2.9 9 7.5 11.7c-1.3 1.7-2.1 3.6-2.1 5.7c0 6.1 6.6 11 14.7 11s14.7-4.9 14.7-11c0-2.1-.8-4-2.1-5.7c4.4-2.7 7.3-7 7.3-11.7");
}

.k50kao52t {
  d: path("M55.3 27.6C55.3 17.9 44.9 10 32 10S8.7 17.9 8.7 27.6c0 2.3.6 4.4 1.6 6.4c-1 2-1.6 4.2-1.6 6.4C8.7 50.1 19.1 58 32 58s23.3-7.9 23.3-17.6c0-2.3-.6-4.4-1.6-6.4c1-2 1.6-4.2 1.6-6.4");
}

.l11lztblz {
  fill: var(--svg-color--3b302a, #3b302a);
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
