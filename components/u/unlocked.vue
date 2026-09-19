<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="e6moybkue"/><path class="mxlubwbhm"/><g class="jeunsn1yj"><ellipse class="vdy3edbkj"/><ellipse class="wv83fibww"/><path class="f0gkprv7y"/></g><path class="smt1eyb1o"/><path class="jez3eunxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:unlocked" /></template>
<style>
.e6moybkue {
  fill: var(--svg-color--ffce31, #ffce31);
  d: path("M2 28.3v31.4C2 62.1 3.9 64 6.3 64h51.4c2.4 0 4.3-1.9 4.3-4.3V28.3z");
}

.f0gkprv7y {
  d: path("m36.6 56.4l-1.9-12.3c1.1-.8 1.9-2.2 1.9-3.7c0-2.5-2-4.6-4.6-4.6s-4.6 2.1-4.6 4.6c0 1.5.7 2.9 1.9 3.7l-1.9 12.3z");
}

.jeunsn1yj {
  fill: var(--svg-color--3e4347, #3e4347);
}

.jez3eunxo {
  fill: var(--svg-color--b0bdc6, #b0bdc6);
  d: path("M51.6 23.5C50.9 12.6 42.4 3.9 32 3.9c-4.4 0-8.6 1.6-11.9 4.3L23 11c2.4-1.8 5.5-3 9-3c9.5 0 15.5 8.4 15.5 15.5c0 .8 2 1.4 4.2 1.4z");
}

.mxlubwbhm {
  fill: var(--svg-color--ff8736, #ff8736);
  d: path("M62 24c0-2.4-1.9-4.3-4.3-4.3H6.3C3.9 19.6 2 21.6 2 24v4.3h60z");
}

.smt1eyb1o {
  fill: var(--svg-color--dfe9ef, #dfe9ef);
  d: path("M32 0c-5.6 0-10.7 2-14.8 5.3l2.9 2.9c3.3-2.7 7.4-4.3 11.9-4.3c10.4 0 18.9 8.7 19.6 19.7V25c2.2 0 3.8-.6 3.8-1.4C55.4 10.6 44.9 0 32 0");
}

.vdy3edbkj {
  cx: 12.4px;
  cy: 23.5px;
  rx: 5.9px;
  ry: 2.5px;
}

.wv83fibww {
  cx: 51.6px;
  cy: 23.5px;
  rx: 5.9px;
  ry: 2.5px;
}

</style>
