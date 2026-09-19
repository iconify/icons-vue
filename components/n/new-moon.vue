<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="phm49tbyx"/><g class="y16l70baz"><circle class="yj94e4bca"/><circle class="h43cugwhq"/><circle class="iptj1fskr"/><circle class="q-ob0owtj"/><circle class="ls1yo1gbk"/><circle class="hg7lxphel"/><circle class="r_w28qzwq"/><circle class="lvjz7-bia"/><circle class="x2stddcav"/><circle class="hqsly9zby"/><circle class="fx05f8yqh"/><circle class="sek9l58ct"/><path class="vtqnjlbta"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:new-moon" /></template>
<style>
.fx05f8yqh {
  cx: 15px;
  cy: 15.7px;
  r: 2px;
}

.h43cugwhq {
  cx: 18.1px;
  cy: 39px;
  r: 6px;
}

.hg7lxphel {
  cx: 12.1px;
  cy: 25.9px;
  r: 4px;
}

.hqsly9zby {
  cx: 25px;
  cy: 29.9px;
  r: 3px;
}

.iptj1fskr {
  cx: 24.2px;
  cy: 50px;
  r: 9px;
}

.ls1yo1gbk {
  cx: 37px;
  cy: 18.2px;
  r: 4px;
}

.lvjz7-bia {
  cx: 8.1px;
  cy: 39px;
  r: 2px;
}

.phm49tbyx {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--3e4347, #3e4347);
}

.q-ob0owtj {
  cx: 24px;
  cy: 17.2px;
  r: 4px;
}

.r_w28qzwq {
  cx: 39px;
  cy: 9.2px;
  r: 2px;
}

.sek9l58ct {
  cx: 46px;
  cy: 52.6px;
  r: 4px;
}

.vtqnjlbta {
  d: path("M24.2 10.8c0 2.8 2.2 5 5 5s5-2.2 5-5s-2.2-5-5-5c-2.8-.1-5 2.2-5 5");
}

.x2stddcav {
  cx: 52px;
  cy: 50px;
  r: 2px;
}

.y16l70baz {
  fill: var(--svg-color--464d51, #464d51);
}

.yj94e4bca {
  cx: 50px;
  cy: 35.2px;
  r: 7px;
}

</style>
