<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="z37nyz-yx"/><rect class="vq5rwbkev"/><path class="gcwx4llyj"/><circle class="o_djt187x"/><circle class="luly1vbjw"/><path class="l46-erb-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:shelf1" /></template>
<style>
.gcwx4llyj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.371 25.79h9.548a3.58 3.58 0 0 1 3.581 3.58v3.424a9 9 0 0 0-2.74-1.322c-1.795-.502-4.092-.474-6.596 1.116c-2.649 1.681-3.52 4.076-3.673 6.158c-.114 1.544.164 2.926.392 3.754h-.512a3.58 3.58 0 0 1-3.58-3.58v-9.55a3.58 3.58 0 0 1 3.58-3.58m8.266 5.394l.711-3.2m-8.045 7.705l-2.581-.731");
}

.l46-erb-j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.665 20.492c-1.722.151-1.708 2.39-3.963 1.516c-1.567-.73-2.674 1.215-4.19-.669c-.992-1.416-2.924-.284-3.295-2.674c-.15-1.722-2.39-1.708-1.515-3.963c.73-1.567-1.216-2.674.668-4.19c1.416-.992.285-2.924 2.675-3.295c1.722-.15 1.708-2.39 3.963-1.515c1.566.73 2.674-1.216 4.19.668c.991 1.416 2.923.285 3.294 2.675c.151 1.722 2.39 1.708 1.516 3.963c-.73 1.566 1.215 2.674-.669 4.19c-1.416.991-.284 2.923-2.674 3.294");
}

.luly1vbjw {
  cx: 38.945px;
  cy: 34.492px;
  r: 0.75px;
  fill: currentColor;
}

.o_djt187x {
  cx: 32.653px;
  cy: 38.31px;
  r: 0.75px;
  fill: currentColor;
}

.vq5rwbkev {
  width: 16.71px;
  height: 16.71px;
  x: 5.5px;
  y: 25.54px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.581px;
  ry: 3.581px;
}

.z37nyz-yx {
  width: 16.71px;
  height: 16.71px;
  x: 25.79px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.581px;
  ry: 3.581px;
}

</style>
