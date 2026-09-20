<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<ellipse class="jogt--mgp"/><ellipse class="f6k-mcjvy"/><path class="cy7idh_og"/><path class="sou88qj9p"/><path class="rr5jribrv"/><path class="lbo26zg5k"/><path class="qoklldgyg"/><path class="lnztw9bhf"/><circle class="ybioeo-lq"/><circle class="u-b-jo48w"/><circle class="aqcs8sepl"/><path class="gmcv8y5bh"/><path class="zeuvflb2m"/><circle class="ucqh_f17p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:robot" /></template>
<style>
.aqcs8sepl {
  cx: 11.5px;
  cy: 14.5px;
  r: 4.5px;
  fill: var(--svg-color--fff, #fff);
}

.cy7idh_og {
  fill: var(--svg-color--ffac33, #ffac33);
  d: path("M34 19a1 1 0 0 1-1 1h-3a1 1 0 0 1-1-1v-9a1 1 0 0 1 1-1h3a1 1 0 0 1 1 1zM7 19a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1v-9a1 1 0 0 1 1-1h3a1 1 0 0 1 1 1z");
}

.f6k-mcjvy {
  cx: 2.5px;
  cy: 14.5px;
  fill: var(--svg-color--f4900c, #f4900c);
  rx: 2.5px;
  ry: 3.5px;
}

.gmcv8y5bh {
  fill: var(--svg-color--f5f8fa, #f5f8fa);
  d: path("M29 25.5a2.5 2.5 0 0 1-2.5 2.5h-17a2.5 2.5 0 1 1 0-5h17a2.5 2.5 0 0 1 2.5 2.5");
}

.jogt--mgp {
  cx: 33.5px;
  cy: 14.5px;
  fill: var(--svg-color--f4900c, #f4900c);
  rx: 2.5px;
  ry: 3.5px;
}

.lbo26zg5k {
  fill: var(--svg-color--269, #269);
  d: path("M30 5.5C30 6.881 28.881 7 27.5 7h-19C7.119 7 6 6.881 6 5.5S7.119 3 8.5 3h19A2.5 2.5 0 0 1 30 5.5");
}

.lnztw9bhf {
  fill: var(--svg-color--3b88c3, #3b88c3);
  d: path("M35 33v-1a2 2 0 0 0-2-2H22.071l-3.364 3.364a1 1 0 0 1-1.414 0L13.929 30H3a2 2 0 0 0-2 2v1c0 1.104-.104 2 1 2h32c1.104 0 1-.896 1-2");
}

.qoklldgyg {
  fill: var(--svg-color--55acee, #55acee);
  d: path("M30 6H6a2 2 0 0 0-2 2v26h28V8a2 2 0 0 0-2-2");
}

.rr5jribrv {
  fill: var(--svg-color--f4900c, #f4900c);
  d: path("M25 4.083C25 5.694 21.865 7 18 7s-7-1.306-7-2.917s3.134-2.917 7-2.917s7 1.306 7 2.917");
}

.sou88qj9p {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
  d: path("M28 5c0 2.761-4.478 4-10 4S8 7.761 8 5s4.477-5 10-5s10 2.239 10 5");
}

.u-b-jo48w {
  cx: 24.5px;
  cy: 14.5px;
  r: 2.721px;
  fill: var(--svg-color--dd2e44, #dd2e44);
}

.ucqh_f17p {
  cx: 11.5px;
  cy: 14.5px;
  r: 2.721px;
  fill: var(--svg-color--dd2e44, #dd2e44);
}

.ybioeo-lq {
  cx: 24.5px;
  cy: 14.5px;
  r: 4.5px;
  fill: var(--svg-color--fff, #fff);
}

.zeuvflb2m {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M17 23h2v5h-2zm-5 0h2v5h-2zm10 0h2v5h-2zM7 25.5a2.5 2.5 0 0 0 2 2.45v-4.9a2.5 2.5 0 0 0-2 2.45m20-2.45v4.899a2.5 2.5 0 0 0 0-4.899");
}

</style>
