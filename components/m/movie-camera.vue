<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="fq--bac7n"/><g class="jeunsn1yj"><path class="wj74yjb6s"/><circle class="qt5l99bzg"/></g><circle class="q5w5wyb4l"/><circle class="ikyb4j05y"/><circle class="l9jl4n_rc"/><path class="playy0b5k"/><path class="koznueumx"/><path class="x_bdxgg7r"/><path class="esc7y7ljn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:movie-camera" /></template>
<style>
.esc7y7ljn {
  fill: var(--svg-color--94989b, #94989b);
  d: path("M21.5 33h16v4h-16zm0-6h16v4h-16z");
}

.fq--bac7n {
  fill: var(--svg-color--94989b, #94989b);
  d: path("M3.6 22c-.6 0-1.1.5-1.1 1.1v19.8c0 .6.5 1.1 1.1 1.1l2.9-.7V22.7z");
}

.ikyb4j05y {
  cx: 49.5px;
  cy: 12px;
  r: 12px;
  fill: var(--svg-color--3e4347, #3e4347);
}

.jeunsn1yj {
  fill: var(--svg-color--3e4347, #3e4347);
}

.koznueumx {
  fill: var(--svg-color--94989b, #94989b);
  d: path("M59.5 41c0 .6-.5 1-1.1 1H20.6c-.6 0-1.1-.4-1.1-1s.5-1 1.1-1h37.8c.6 0 1.1.4 1.1 1m-18-15h16v12h-16z");
}

.l9jl4n_rc {
  cx: 49.5px;
  cy: 12px;
  r: 4px;
  fill: var(--svg-color--94989b, #94989b);
}

.playy0b5k {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M61.5 42.9c0 .6-.5 1.1-1.1 1.1H18.6c-.6 0-1.1-.5-1.1-1.1V23.1c0-.6.5-1.1 1.1-1.1h41.8c.6 0 1.1.5 1.1 1.1z");
}

.q5w5wyb4l {
  cx: 29.5px;
  cy: 12px;
  r: 4px;
  fill: var(--svg-color--94989b, #94989b);
}

.qt5l99bzg {
  cx: 29.5px;
  cy: 12px;
  r: 12px;
}

.wj74yjb6s {
  d: path("M6.5 22.7v20.6l40-10.3zm36 18.3h-5l-9 21h-4.1v2h6.7l7.4-18v16h-3v2h9v-2h-3V46l7.6 18h6.4v-2h-4z");
}

.x_bdxgg7r {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M42.5 27h14v10h-14z");
}

</style>
