<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="o28r8bcaf"/><path class="kd19xbr9v"/><path class="da6hxi2et"/><ellipse class="vozyi8bbv"/><ellipse class="pq-ubub0i"/><ellipse class="gqjb49bnf"/><path class="n30gm2blc"/><path class="c7niupb2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:salt" /></template>
<style>
.c7niupb2e {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M23.472 8H12.528c-.657 0-1.213.417-1.429 1H24.9c-.215-.583-.77-1-1.428-1M11 10h14v1H11zm0 2h14v.5H11z");
}

.da6hxi2et {
  fill: var(--svg-color--f5f8fa, #f5f8fa);
  d: path("M19.344 14h-6.802a1 1 0 0 0-.986.836l-3 18A.998.998 0 0 0 9.541 34h10.427zm5.101.836a1 1 0 0 0-.986-.836h-2.413l.909 20h4.505a1 1 0 0 0 .986-1.164z");
}

.gqjb49bnf {
  cx: 18px;
  cy: 3.5px;
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  rx: 1.2px;
  ry: 0.6px;
}

.kd19xbr9v {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M24.306 12H11.694a2 2 0 0 0-1.973 1.671l-3.333 20A2 2 0 0 0 8.361 36h19.278a2 2 0 0 0 1.973-2.329l-3.333-20A2 2 0 0 0 24.306 12");
}

.n30gm2blc {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M25 12H11V9.528c0-.844.684-1.262 1.528-1.262h10.944c.844 0 1.528.418 1.528 1.262z");
}

.o28r8bcaf {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M26 4c0 3-3.582 6-8 6s-8-3-8-6c0-4.418 6-4 8-4s8-.418 8 4");
}

.pq-ubub0i {
  cx: 21px;
  cy: 1.5px;
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  rx: 1.2px;
  ry: 0.6px;
}

.vozyi8bbv {
  cx: 15px;
  cy: 1.5px;
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  rx: 1.2px;
  ry: 0.6px;
}

</style>
