<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="q0h1pzbma"/><ellipse class="qk9tilxzc"/><ellipse class="mbh5anb_r"/><ellipse class="x9zys9b1n"/><path class="cj8wfdbkr"/><path class="xrh6snbyr"/><path class="fnszj8n5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mame4droid-alt-1" /></template>
<style>
.cj8wfdbkr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.579 25.588h6.842m-7.042 2.736h7.242m-7.442 2.736h7.643m-13.555.2v4.435m-7.029-9.098c.271-1.463 1.598-3.424 3.674-3.424c-2.076 0-3.403-1.961-3.674-3.424c0 0-1.644-8.62-1.738-11.076c0-2.216 1.784-4 4-4h29c2.216 0 4 1.784 4 4c-.094 2.455-1.738 11.076-1.738 11.076c-.271 1.463-1.598 3.424-3.674 3.424c2.076 0 3.403 1.961 3.674 3.424c0 0 1.644 8.621 1.738 11.076c0 2.216-1.784 4-4 4h-29c-2.216 0-4-1.784-4-4c.094-2.455 1.738-11.076 1.738-11.076m3.674-3.424h.511m25.665 0H17.175");
}

.fnszj8n5x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.705 13.85V8.22l-4.475 5.63V8.22l-4.475 5.63V8.22l-6.522 7.742");
}

.mbh5anb_r {
  cx: 27.823px;
  cy: 36.341px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.687px;
  ry: 2.279px;
}

.q0h1pzbma {
  cx: 14.267px;
  cy: 26.671px;
  r: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.qk9tilxzc {
  cx: 14.267px;
  cy: 35.91px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 2.2px;
}

.x9zys9b1n {
  cx: 35.935px;
  cy: 32.452px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.687px;
  ry: 2.279px;
}

.xrh6snbyr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m21.493 20.902l4.306-5.256v3.825m1.651-3.825v3.825h4.011M29.1 15.646v3.825m5.801 22.203c-.066.923-1.518 1.653-3.288 1.653s-3.222-.73-3.288-1.653M18.012 13.85V8.22l-4.475 5.63V8.22l-4.742 5.63m28.203 0h-5.293l4.742-5.63h2.758m-5.128 2.816h1.887m-13.652 5.05h-3.99l2.736-3.296v4.234");
}

</style>
