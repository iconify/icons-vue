<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<g class="otdye5b3i"><path class="cr8rwqbcs"/><path class="y9z4n8h0u"/></g><path class="xnclxdbvo"/><path class="vbd-lkb2w"/><path class="inn5so-if"/><path class="o-vvymw4u"/><path class="hbm4w1mcz"/><path class="gquyqkhit"/><g class="r2_de7jrh"><ellipse class="ctl3650xz"/><ellipse class="v03605m5m"/></g><path class="b7xw2w1rv"/><path class="pyf1a-bvb"/><path class="s7t4oqv4h"/><path class="i83y0rhsb"/><path class="u-egvr3-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:tear-off-calendar" /></template>
<style>
.b7xw2w1rv {
  fill: var(--svg-color--e8edef, #e8edef);
  d: path("M35 9.5L47.4 14s.5.3.2 2.4c-.5-.1-.9-.8-.9-.8L34.2 11c.1-.1-.1-.4.8-1.5");
}

.cr8rwqbcs {
  d: path("M2 34.2h3.6v5.9H2zm56.3-15.8h3.6v5.9h-3.6z");
}

.ctl3650xz {
  cx: 33.5px;
  cy: 9.8px;
  rx: 1.6px;
  ry: 1.3px;
}

.gquyqkhit {
  fill: var(--svg-color--93a2aa, #93a2aa);
  d: path("M60.2 22.7v5.9l1.6-4l.2-7.3z");
}

.hbm4w1mcz {
  fill: var(--svg-color--c7d3d8, #c7d3d8);
  d: path("M61.8 18.2c.3-1 .5-1.8-1.8-2.5L27.3 4.5c-2.1-.8-2.8-.6-4 .9l-2.7 3.2l39.6 14.1z");
}

.i83y0rhsb {
  fill: var(--svg-color--fff, #fff);
  d: path("m28.3 17.9l-.1.1c-.3.5-.4.9-.4 1.1s.1.4.5.6c.3.1.6.1.8-.1c.1-.1.3-.3.5-.7l2.6-4.7l1.5.5l-2.7 4.9c-.3.6-.7 1-1.1 1.2c-.7.4-1.4.5-2.3.1c-.9-.3-1.3-.8-1.3-1.4s.1-1.2.6-2l.1-.2zm6.9-2.5l1.6.6l-2.4 4.2c-.3.5-.4.8-.4 1.1c0 .5.3.8.9 1.1c.6.2 1.1.2 1.6-.1c.2-.2.5-.5.8-1l2.4-4.3l1.7.6l-2.5 4.4c-.4.7-.9 1.3-1.4 1.6c-.9.6-2 .6-3.3.1s-1.9-1.2-1.9-2.1q0-.75.6-1.8zm7.7 2.7l1.7.6l-3.3 5.9l4.1 1.6l-.8 1.3l-5.7-2.3z");
}

.inn5so-if {
  fill: var(--svg-color--333, #333);
  d: path("M4.2 30.3c-1.2 1.5.3 3.8 1.5 4.9c4.7 4.3 23 12.3 23 12.3z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.o-vvymw4u {
  fill: var(--svg-color--d9e3e8, #d9e3e8);
  d: path("M14.4 17s-3.8 5.3-7 6.8c-2.4 1.1-3.8 0-4.4 1.8C0 36.2 42.6 54 42.6 54c2 .9 4.3 0 5.1-1.9L55.8 33z");
}

.otdye5b3i {
  fill: var(--svg-color--819096, #819096);
}

.pyf1a-bvb {
  fill: var(--svg-color--93a2aa, #93a2aa);
  d: path("m34.7 9.9l12.4 4.5s.3.4.3 1.8c-.4-.3-.6-.7-.6-.7l-12.5-4.6s-.2-.2.4-1");
}

.r2_de7jrh {
  fill: var(--svg-color--69787c, #69787c);
}

.s7t4oqv4h {
  fill: var(--svg-color--69787c, #69787c);
  d: path("M20.6 8.9v-.3l39.6 14.1v6.2H60l.1-5.9z");
}

.u-egvr3-d {
  fill: var(--svg-color--333, #333);
  d: path("m19 27.7l1.1-1.9q1.5.45 2.1.6c.7.1 1.3.1 1.9-.2c.4-.1.8-.4 1.2-.8l.5-.5l2.5 1L20 40.2L16.9 39l5.8-9.8zm23.3 6.8c-.7.2-1.8.7-3.2 1.4s-2.7 1.5-4 2.5c-1 .7-2 1.6-3.1 2.8c-1.1 1.1-1.9 2.1-2.4 2.9l-3.1-1.3c1.6-2.5 4-4.8 7.4-6.8c2.1-1.3 3.7-2.1 4.9-2.4l-7.7-3.1l1.5-2.5l10.9 4.3z");
}

.v03605m5m {
  cx: 48.3px;
  cy: 15.1px;
  rx: 1.6px;
  ry: 1.3px;
}

.vbd-lkb2w {
  fill: var(--svg-color--cad5dd, #cad5dd);
  d: path("M14.4 17L2.7 32.3c-1.2 1.5-.8 3.4.9 4.2l39.3 17.3c2 .9 4.3 0 5.1-1.9l7.9-18.8z");
}

.xnclxdbvo {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M61.7 19.1c.5-1.2-.4-2.7-2-3.3L27.3 4.5c-1.4-.5-3.2-.1-4 .9L14.4 17l41.4 16.1z");
}

.y9z4n8h0u {
  d: path("M59.7 21.7L27.3 10.4c-1.4-.5-3.2-.1-4 .9l-8.9 11.6L2.7 38.2c-1.2 1.5-.8 3.4.9 4.2l39.3 17.3c2 .9 4.3 0 5.1-1.9L55.8 39l5.9-14c.5-1.2-.4-2.7-2-3.3");
}

</style>
