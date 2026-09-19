<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<g class="jeunsn1yj"><path class="ht_gevbfl"/><circle class="alx35cccf"/><path class="g_98zj2wu"/><circle class="z4-9j2p-v"/><ellipse class="mo24w1-ti"/></g><path class="tq_0psbwr"/><g class="jeunsn1yj"><path class="ryimz2_sh"/><circle class="m613mjvjw"/><circle class="fslisabzf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:television" /></template>
<style>
.alx35cccf {
  cx: 19px;
  cy: 3.4px;
  r: 1.4px;
}

.fslisabzf {
  cx: 56.4px;
  cy: 37.6px;
  r: 2.8px;
}

.g_98zj2wu {
  d: path("m28.78 19.017l15.909-15.91l.636.637l-15.91 15.91z");
}

.ht_gevbfl {
  d: path("M17 62H5.8c0-2.6 2.5-4.7 5.6-4.7S17 59.4 17 62m41.2 0H47c0-2.6 2.5-4.7 5.6-4.7s5.6 2.1 5.6 4.7M18.59 3.758l.636-.636l15.903 15.916l-.637.636z");
}

.jeunsn1yj {
  fill: var(--svg-color--3e4347, #3e4347);
}

.m613mjvjw {
  cx: 56.4px;
  cy: 29.2px;
  r: 2.8px;
}

.mo24w1-ti {
  cx: 32px;
  cy: 15.1px;
  rx: 8px;
  ry: 4.7px;
}

.ryimz2_sh {
  d: path("M49.5 52.7c-3.9 5-35.6 4.9-40.3 0c-3.4-3.6-3.4-24.7 0-28.2c4.7-4.9 36.4-5 40.3 0c2.9 3.7 2.9 24.5 0 28.2");
}

.tq_0psbwr {
  fill: var(--svg-color--c28fef, #c28fef);
  d: path("M59.1 57.1c-5.2 6.6-47.5 6.4-53.7 0c-4.6-4.7-4.6-32.5 0-37.2c6.2-6.4 48.5-6.6 53.7 0c3.9 5 3.9 32.3 0 37.2");
}

.z4-9j2p-v {
  cx: 45px;
  cy: 3.4px;
  r: 1.4px;
}

</style>
