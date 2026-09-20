<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="lfh4txbnr"/><path class="rhvm0qbbb"/><path class="l4nw17blw"/><path class="eo9ju8b7p"/><path class="n4xns7rzz"/><path class="ytvcj9btt"/><path class="bx7w9acob"/><circle class="anq86q84s"/><path class="g9oc78bfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:printer" /></template>
<style>
.anq86q84s {
  cx: 30.5px;
  cy: 19.5px;
  r: 1.5px;
  fill: var(--svg-color--f5f8fa, #f5f8fa);
}

.bx7w9acob {
  fill: var(--svg-color--9aaab4, #9aaab4);
  d: path("M25 29a1 1 0 0 1-1 1H12a1 1 0 1 1 0-2h12a1 1 0 0 1 1 1");
}

.eo9ju8b7p {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M30 25c0-1.104-.978-2-2.182-2H8.182C6.977 23 6 23.896 6 25v4h24z");
}

.g9oc78bfq {
  fill: var(--svg-color--9aaab4, #9aaab4);
  d: path("M25 32a1 1 0 0 1-1 1H12a1 1 0 1 1 0-2h12a1 1 0 0 1 1 1M9 25h18v2H9z");
}

.l4nw17blw {
  fill: var(--svg-color--5dadec, #5dadec);
  d: path("M34 25c0 1-1 3-3 3H5c-2 0-3-2-3-3v-9a4 4 0 0 1 4-4h24a4 4 0 0 1 4 4z");
}

.lfh4txbnr {
  fill: var(--svg-color--67757f, #67757f);
  d: path("M30 12H6V5c0-1.105.826-2 1.846-2h20.309C29.173 3 30 3.895 30 5zm0 19a2 2 0 0 1-2 2H8a2 2 0 0 1-2-2v-3h24z");
}

.n4xns7rzz {
  fill: var(--svg-color--4289c1, #4289c1);
  d: path("M30 15a2 2 0 0 1-2 2H8a2 2 0 0 1-2-2v-4h24z");
}

.rhvm0qbbb {
  fill: var(--svg-color--e1e8ed, #e1e8ed);
  d: path("M27 12H9V2a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2z");
}

.ytvcj9btt {
  fill: var(--svg-color--e1e8ed, #e1e8ed);
  d: path("M27 34a2 2 0 0 1-2 2H11a2 2 0 0 1-2-2v-8h18z");
}

</style>
