<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="u5nbzddmm"/><path class="qn0bb1bqp"/><ellipse class="w7-rxlb0s"/><g class="aaj16gswv"><circle transform="rotate(-59.982 22.405 43.953)" class="tef6c4b3w"/><circle transform="rotate(-59.987 41.597 10.715)" class="kmay-jyaf"/><circle transform="rotate(-30 15.378 36.934)" class="wq2yqgafl"/><circle transform="rotate(-30.021 48.624 17.743)" class="y0nzwzbzb"/><circle class="wqpmb8n6h"/><circle class="jiv_pubyw"/><circle transform="rotate(-59.987 15.38 17.742)" class="dl2e3iyof"/><circle transform="rotate(-59.979 48.62 36.933)" class="vs8xrf5mn"/><circle transform="rotate(-30.006 22.405 10.716)" class="eb957uqvp"/><path class="d10i9obgz"/><circle class="c7g4n_dvv"/><circle class="c0blrxbeo"/></g><circle class="k2mc73bfr"/><circle class="yncsiyb3h"/><path class="zy9w0pgjj"/><path class="y912o4oyn"/><path class="ucucdnbtt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:timer-clock" /></template>
<style>
.aaj16gswv {
  fill: var(--svg-color--f5f5f5, #f5f5f5);
}

.c0blrxbeo {
  cx: 32px;
  cy: 46.5px;
  r: 1.3px;
}

.c7g4n_dvv {
  cx: 32px;
  cy: 8.1px;
  r: 1.3px;
}

.d10i9obgz {
  d: path("M42.7 43.3c.4.6.2 1.4-.5 1.8c-.6.4-1.4.1-1.8-.5s-.2-1.4.5-1.8c.7-.3 1.5-.1 1.8.5");
}

.dl2e3iyof {
  cx: 15.4px;
  cy: 17.7px;
  r: 1.3px;
}

.eb957uqvp {
  cx: 22.4px;
  cy: 10.7px;
  r: 1.3px;
}

.jiv_pubyw {
  cx: 51.2px;
  cy: 27.3px;
  r: 1.3px;
}

.k2mc73bfr {
  cx: 32px;
  cy: 27.3px;
  r: 16px;
  fill: var(--svg-color--b0bcc1, #b0bcc1);
}

.kmay-jyaf {
  cx: 41.6px;
  cy: 10.7px;
  r: 1.3px;
}

.qn0bb1bqp {
  fill: var(--svg-color--055672, #055672);
  d: path("M59 46.1c0 4.6-5.2 13.5-27 13.5s-27-9-27-13.5c0-2.1 7.9 7.7 27 7.7s27-9.9 27-7.7");
}

.tef6c4b3w {
  cx: 22.4px;
  cy: 44px;
  r: 1.3px;
}

.u5nbzddmm {
  fill: var(--svg-color--13618d, #13618d);
  d: path("M62 38.1C62 57.5 48.6 61 32 61S2 57.5 2 38.1S15.4 3 32 3s30 15.7 30 35.1");
}

.ucucdnbtt {
  fill: var(--svg-color--fff, #fff);
  d: path("M36.1 29.1c0 6.1-8.3 6.1-8.3 0s1.9-17.7 4.1-17.7c2.4 0 4.2 11.6 4.2 17.7");
}

.vs8xrf5mn {
  cx: 48.6px;
  cy: 36.9px;
  r: 1.3px;
}

.w7-rxlb0s {
  cx: 32px;
  cy: 27.3px;
  fill: var(--svg-color--428bc1, #428bc1);
  rx: 22.5px;
  ry: 22.8px;
}

.wq2yqgafl {
  cx: 15.4px;
  cy: 36.9px;
  r: 1.3px;
}

.wqpmb8n6h {
  cx: 12.8px;
  cy: 27.3px;
  r: 1.3px;
}

.y0nzwzbzb {
  cx: 48.6px;
  cy: 17.7px;
  r: 1.3px;
}

.y912o4oyn {
  fill: var(--svg-color--e4e7ea, #e4e7ea);
  d: path("M36.9 31.8c0 7-9.9 7-9.9 0s2.2-20.5 4.9-20.5c2.8 0 5 13.5 5 20.5");
}

.yncsiyb3h {
  cx: 32px;
  cy: 25.9px;
  r: 14.5px;
  fill: var(--svg-color--f5f5f5, #f5f5f5);
}

.zy9w0pgjj {
  fill: var(--svg-color--b0bcc1, #b0bcc1);
  d: path("M37.7 33.3c0 7.3-11.3 7.3-11.3 0C26.3 26 28.9 12 32 12s5.7 14 5.7 21.3");
}

</style>
