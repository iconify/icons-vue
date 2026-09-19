<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="w7djv65bj"/><circle class="n7g2_vbmx"/><circle class="l30ayxbuy"/><circle class="i9wzkyucx"/><path class="x3-hwtb5j"/><g class="f0zp6fbvj"><ellipse class="n86im8bbl"/><ellipse class="l7lku1b8g"/></g><path class="pinkvab7k"/><ellipse class="nzv8jfbyj"/><ellipse class="zo3qvqqsk"/><ellipse class="fahk-tbrd"/><g class="jeunsn1yj"><ellipse class="xgrofp7sp"/><path class="j4-a_ddpo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:mouse-face" /></template>
<style>
.f0zp6fbvj {
  fill: var(--svg-color--ffc5d3, #ffc5d3);
}

.fahk-tbrd {
  cx: 40.9px;
  cy: 38.5px;
  fill: var(--svg-color--fff, #fff);
  rx: 6px;
  ry: 5.9px;
}

.i9wzkyucx {
  cx: 15.7px;
  cy: 21.3px;
  r: 10.1px;
  fill: var(--svg-color--ffc5d3, #ffc5d3);
}

.j4-a_ddpo {
  d: path("M30.7 55.1c.1-.4.4-.7.7-.9l.9-.6c.3-.1.7-.2 1.1-.3c.4 0 .8 0 1.1.3c-.4 0-.6.2-.9.3l-.9.4c-.3.1-.6.3-.9.4c-.4.1-.8.2-1.1.4");
}

.jeunsn1yj {
  fill: var(--svg-color--3e4347, #3e4347);
}

.l30ayxbuy {
  cx: 15.6px;
  cy: 19.6px;
  r: 13.6px;
  fill: var(--svg-color--b5b5b5, #b5b5b5);
}

.l7lku1b8g {
  cx: 19.3px;
  cy: 47.8px;
  rx: 4.2px;
  ry: 2.9px;
}

.n7g2_vbmx {
  cx: 48.3px;
  cy: 21.3px;
  r: 10.1px;
  fill: var(--svg-color--ffc5d3, #ffc5d3);
}

.n86im8bbl {
  cx: 44.7px;
  cy: 47.8px;
  rx: 4.2px;
  ry: 2.9px;
}

.nzv8jfbyj {
  cx: 23.1px;
  cy: 38.5px;
  fill: var(--svg-color--fff, #fff);
  rx: 6px;
  ry: 5.9px;
}

.pinkvab7k {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M35.8 47.8c-.8-.8-3.1-.9-3.8-.9s-3 .1-3.8.9c-.5.6-.1 2 1.3 3.2c.9.8 1.8 1 2.5 1s1.6-.2 2.5-1c1.4-1.2 1.8-2.6 1.3-3.2");
}

.w7djv65bj {
  cx: 48.4px;
  cy: 19.6px;
  r: 13.6px;
  fill: var(--svg-color--b5b5b5, #b5b5b5);
}

.x3-hwtb5j {
  fill: var(--svg-color--c4c5c6, #c4c5c6);
  d: path("M48.5 33.4c-2.2-5-7.5-16-16.5-16s-14.3 11-16.5 16c-1.1 2.6-2.1 5-2.5 8.7c-.6 6.5 7 12 11.1 12c2 0 4.1 3.9 7.9 3.9s5.9-3.9 7.9-3.9c4.1 0 11.7-5.6 11.1-12c-.4-3.7-1.4-6.2-2.5-8.7");
}

.xgrofp7sp {
  cx: 40.9px;
  cy: 38.5px;
  rx: 4.2px;
  ry: 4.1px;
}

.zo3qvqqsk {
  cx: 23.1px;
  cy: 38.5px;
  fill: var(--svg-color--3e4347, #3e4347);
  rx: 4.2px;
  ry: 4.1px;
}

</style>
