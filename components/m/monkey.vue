<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<g class="euxxm2bmm"><path class="idth-lbhg"/><path class="hvdu0c-3t"/></g><path class="a4rqk5bqi"/><path class="qf8wklb1g"/><path class="n1ggkxxbo"/><circle class="mezjxeb1z"/><circle class="zkn_34avo"/><circle class="pmr5pebml"/><circle class="s7zcncb_l"/><g class="euxxm2bmm"><path class="zd9-05o9t"/><path class="z5_nk-bnh"/></g><path class="ajnf10bir"/><g class="l11lztblz"><ellipse class="j3lp25y4c"/><ellipse class="syderbbnr"/><ellipse class="nh7gwibod"/><ellipse class="kwe36240t"/><path class="xryz3itvf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:monkey" /></template>
<style>
.a4rqk5bqi {
  fill: var(--svg-color--e0ac7e, #e0ac7e);
  d: path("M23.5 57.8c-2.4 1-8.4 1.5-6.9 4.2h11.9c1.9-2.7-1.8-5.6-5-4.2m15-3.6s-1.9-11.2-10.4-13c-8.4-1.8-3.4-4.6.9-3.6c10.5 2.3 9.5 16.6 9.5 16.6");
}

.ajnf10bir {
  fill: var(--svg-color--e0ac7e, #e0ac7e);
  d: path("M37.6 17.8c0-12-14.2-4.4-14.2-4.4S9.1 5.8 9.1 17.8c0 3.4 2.1 6.4 5.3 8.3c-.9 1.2-1.5 2.6-1.5 4c0 4.3 4.7 7.8 10.4 7.8c5.8 0 10.4-3.5 10.4-7.8c0-1.5-.6-2.9-1.5-4c3.3-1.9 5.4-4.9 5.4-8.3");
}

.euxxm2bmm {
  fill: var(--svg-color--89664c, #89664c);
}

.hvdu0c-3t {
  d: path("m30 27.9l-1.9 13.4c-4.9 0-6.1 9.1-4.7 17.5c.1.8 5.5 1.7 5.5 1.7c-1-5.3.4-7.9.4-7.9c-.3 4.7.3 9.5 8.4 9.5c7.5 0 11.6-2.6 12-9.5C50.9 30.6 30 27.9 30 27.9");
}

.idth-lbhg {
  d: path("M50.4 59.9c-2.5 0-4.7-1.2-5.5-1.7c-.9-.5-1.2-1.7-.7-2.6s1.7-1.2 2.6-.7c2.2 1.2 3.9 1.5 5.2.9c1.6-.7 3.8-3.2 5.4-10.6c1.4-6.7 1.5-15.6-1.6-19.4c-.9-1.2-2.1-1.7-3.6-1.7c-3.6 0-4.6 2.5-4.6 3.9c0 .4.1 2.1 1.6 2.1c.3 0 .7-.1 1-.5q.45-.6.3-1.5c-.2-1 .5-2 1.5-2.2s2 .5 2.2 1.5c.3 1.7 0 3.4-1.1 4.6c-1 1.2-2.5 1.9-4 1.9c-3.1 0-5.3-2.5-5.3-5.9c0-1.9.8-3.8 2.1-5.2c1.1-1.1 3-2.5 6.3-2.5c2.6 0 4.9 1.1 6.5 3.1c4.1 5.1 3.8 15.3 2.3 22.5c-1.5 7.3-4 11.7-7.5 13.3c-1 .6-2.1.7-3.1.7");
}

.j3lp25y4c {
  cx: 24.9px;
  cy: 25.3px;
  rx: 0.7px;
  ry: 1.5px;
}

.kwe36240t {
  cx: 17.2px;
  cy: 20.3px;
  rx: 2.5px;
  ry: 3.2px;
}

.l11lztblz {
  fill: var(--svg-color--3b302a, #3b302a);
}

.mezjxeb1z {
  cx: 38.8px;
  cy: 21.2px;
  r: 5.9px;
  fill: var(--svg-color--89664c, #89664c);
}

.n1ggkxxbo {
  fill: var(--svg-color--e0ac7e, #e0ac7e);
  d: path("M14.8 57.3c-1.9-2.3-4.8.7-6.3 1.8c-.7.5-4.5.6-3.3 2.9h8.2c2.6-.8 2.5-3.3 1.4-4.7");
}

.nh7gwibod {
  cx: 29.5px;
  cy: 20.3px;
  rx: 2.5px;
  ry: 3.2px;
}

.pmr5pebml {
  cx: 7.9px;
  cy: 21.2px;
  r: 5.9px;
  fill: var(--svg-color--89664c, #89664c);
}

.qf8wklb1g {
  fill: var(--svg-color--89664c, #89664c);
  d: path("M27.9 36.6h-9.5L12 57.1l3.2 3.5z");
}

.s7zcncb_l {
  cx: 7.9px;
  cy: 21.2px;
  r: 3.8px;
  fill: var(--svg-color--ffc5d3, #ffc5d3);
}

.syderbbnr {
  cx: 21.8px;
  cy: 25.3px;
  rx: 0.7px;
  ry: 1.5px;
}

.xryz3itvf {
  d: path("M30.4 30.6c.4 1.1-2.7 3.3-7.1 3.3s-7.5-2.2-7.1-3.3c.5-1.1 13.8-1.1 14.2 0");
}

.z5_nk-bnh {
  d: path("M39.9 17.3c0-6.9-7.4-12.5-16.6-12.5S6.7 10.4 6.7 17.3c0 1.6.4 3.2 1.2 4.6c-.7 1.4-1.2 3-1.2 4.6c0 6.9 7.4 12.5 16.6 12.5s16.6-5.6 16.6-12.5c0-1.6-.4-3.2-1.2-4.6c.8-1.4 1.2-2.9 1.2-4.6");
}

.zd9-05o9t {
  d: path("M31.4 5.4c.8-.4 1.3-.6 1.3-.6q-3.45-1.2-6-1.5c.9-.7 1.5-.9 1.5-.9C13.7.3 6.8 8.7 6.8 16.2h33c-.4-5.2-3.3-8.8-8.4-10.8");
}

.zkn_34avo {
  cx: 38.8px;
  cy: 21.2px;
  r: 3.8px;
  fill: var(--svg-color--ffc5d3, #ffc5d3);
}

</style>
