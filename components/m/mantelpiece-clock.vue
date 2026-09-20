<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="hnccc5b7h"/><path class="zpa48hnag"/><path class="ifgoc0b2j"/><path class="ogfjbdbvw"/><path class="e8xoycv9b"/><path class="kk1qs947v"/><path class="f5d8ff8ng"/><circle class="g8-pinbzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:mantelpiece-clock" /></template>
<style>
.e8xoycv9b {
  fill: var(--svg-color--f5f8fa, #f5f8fa);
  d: path("M26 20a8 8 0 1 1-16 0a8 8 0 0 1 16 0");
}

.f5d8ff8ng {
  fill: var(--svg-color--c1694f, #c1694f);
  d: path("M19 16.5c0 1.933-.448 3.5-1 3.5s-1-1.566-1-3.5s1-3.499 1-3.499c0-.001 1 1.566 1 3.499");
}

.g8-pinbzf {
  cx: 18px;
  cy: 20px;
  r: 0.586px;
  fill: var(--svg-color--662113, #662113);
}

.hnccc5b7h {
  fill: var(--svg-color--662113, #662113);
  d: path("m2 29l-1 6h8s1-2 3-2h6v-4zm32 0l1 6h-8s-1-2-3-2h-6v-4zM6 20c0 1 0 8-4 8l8 1zm24 0c0 1 0 8 4 8l-8 1z");
}

.ifgoc0b2j {
  fill: var(--svg-color--a0041e, #a0041e);
  d: path("M10 35a1 1 0 0 1-1 1H1a1 1 0 1 1 0-2h8a1 1 0 0 1 1 1m26 0a1 1 0 0 1-1 1h-8a1 1 0 1 1 0-2h8a1 1 0 0 1 1 1m-1-6a1 1 0 0 1-1 1H2a1 1 0 1 1 0-2h32a1 1 0 0 1 1 1");
}

.kk1qs947v {
  fill: var(--svg-color--c1694f, #c1694f);
  d: path("M18 20s-.119 1-1.5 1s-3.5-1-3.5-1s2.119-1 3.5-1s1.5 1 1.5 1");
}

.ogfjbdbvw {
  fill: var(--svg-color--ffac33, #ffac33);
  d: path("M27 20a9 9 0 1 1-18 0a9 9 0 0 1 18 0");
}

.zpa48hnag {
  fill: var(--svg-color--662113, #662113);
  d: path("M30 20c0 6.628-5.373 12-12 12S6 26.628 6 20c0-6.627 5.373-12 12-12s12 5.373 12 12");
}

</style>
