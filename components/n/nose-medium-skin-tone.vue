<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<g class="c0lrhybse"><ellipse class="lrgr58i4w"/><ellipse class="t99tb-gix"/></g><g class="wgyg6qglv"><path class="k8ew9cybl"/><path class="dfaq8l_wz"/></g><path class="wtyyy5brb"/><path class="x3vf_wx5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:nose-medium-skin-tone" /></template>
<style>
.c0lrhybse {
  fill: var(--svg-color--d6a57c, #d6a57c);
}

.dfaq8l_wz {
  d: path("M32 53.3c-3.1 0-7-.9-12.4-2l1.1 6.1C23.6 60.2 27.6 62 32 62s8.4-1.8 11.3-4.6l1.1-6.1c-5.4 1.1-9.3 2-12.4 2");
}

.k8ew9cybl {
  d: path("M47.1 49.4c-3.8 0-6.9 2.1-6.9 4.7c0 .6.2 1.2.5 1.8c1.7 1.4 3.9 2.3 6.4 2.3c2.4 0 4.7-.9 6.4-2.3c.3-.5.5-1.1.5-1.8c0-2.6-3-4.7-6.9-4.7m-30.2 0c3.8 0 6.9 2.1 6.9 4.7c0 .6-.2 1.2-.5 1.8c-1.7 1.4-3.9 2.3-6.4 2.3c-2.4 0-4.7-.9-6.4-2.3c-.3-.5-.5-1.1-.5-1.8c0-2.6 3-4.7 6.9-4.7");
}

.lrgr58i4w {
  cx: 16.9px;
  cy: 48.6px;
  rx: 9.9px;
  ry: 9.5px;
}

.t99tb-gix {
  cx: 47.1px;
  cy: 48.6px;
  rx: 9.9px;
  ry: 9.5px;
}

.wgyg6qglv {
  fill: var(--svg-color--cf9364, #cf9364);
}

.wtyyy5brb {
  fill: var(--svg-color--935e3e, #935e3e);
  d: path("M17.6 53.2c3.7 1.1 4.7 5.6 4.7 5.6s-2.5-1.9-5.4-2.5c-6.7-1.4-3.8-4.6.7-3.1m28.8 0c-3.7 1.1-4.7 5.6-4.7 5.6s2.5-1.9 5.4-2.5c6.8-1.4 3.8-4.6-.7-3.1");
}

.x3vf_wx5g {
  fill: var(--svg-color--d6a57c, #d6a57c);
  d: path("M43 21.2C43 5 38.1 2 32 2S20.9 5 20.9 21.2c0 4.7-3.7 18.4-3.7 24c0 8.3 6.6 8.6 14.8 8.6s14.8-.3 14.8-8.6c0-5.6-3.8-19.3-3.8-24");
}

</style>
