<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="q0h1pzbma"/><ellipse class="qk9tilxzc"/><ellipse class="mbh5anb_r"/><ellipse class="x9zys9b1n"/><path class="cj8wfdbkr"/><path class="lb-7lnbpp"/><circle class="uj3tcs9gh"/><circle class="nn67j-b1p"/><path class="x2-4v1b1r"/><path class="jnqous_7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mame4droid" /></template>
<style>
.cj8wfdbkr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.579 25.588h6.842m-7.042 2.736h7.242m-7.442 2.736h7.643m-13.555.2v4.435m-7.029-9.098c.271-1.463 1.598-3.424 3.674-3.424c-2.076 0-3.403-1.961-3.674-3.424c0 0-1.644-8.62-1.738-11.076c0-2.216 1.784-4 4-4h29c2.216 0 4 1.784 4 4c-.094 2.455-1.738 11.076-1.738 11.076c-.271 1.463-1.598 3.424-3.674 3.424c2.076 0 3.403 1.961 3.674 3.424c0 0 1.644 8.621 1.738 11.076c0 2.216-1.784 4-4 4h-29c-2.216 0-4-1.784-4-4c.094-2.455 1.738-11.076 1.738-11.076m3.674-3.424h.511m25.665 0H17.175");
}

.jnqous_7i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.705 13.85V8.223L27.23 13.85V8.22l-4.475 5.63V8.22l-6.522 7.742");
}

.lb-7lnbpp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.534 20.413a6.3 6.3 0 1 1 12.6 0zm9.156-5.615l1.054-1.422M28.981 14.8l-1.057-1.425");
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

.nn67j-b1p {
  cx: 34.161px;
  cy: 17.212px;
  r: 0.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
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

.uj3tcs9gh {
  cx: 29.508px;
  cy: 17.212px;
  r: 0.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.x2-4v1b1r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.534 23.173V20.68c0-.742-.591-1.23-1.239-1.23s-1.238.532-1.238 1.23v2.492m15.077-2.759v2.76m-3.233 18.501c-.066.923-1.518 1.653-3.288 1.653s-3.222-.73-3.288-1.653M18.013 13.85V8.223l-4.475 5.629V8.22l-4.742 5.63m28.202 0h-5.293l4.742-5.628h2.758m-5.128 2.814h1.887m-13.652 5.051h-3.99l2.736-3.296v4.234");
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

</style>
