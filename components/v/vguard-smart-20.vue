<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uipahhprt"/><path class="r3ilz2boi"/><rect class="hi7izor8p"/><path class="p4y62ikxs"/><rect class="wbc93aban"/><circle class="zn2n_rbwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vguard-smart-20" /></template>
<style>
.hi7izor8p {
  width: 36px;
  height: 36px;
  x: 6px;
  y: 6px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.892px;
  ry: 3.892px;
}

.p4y62ikxs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.428 32.359a2.653 2.653 0 0 1 3.176-2.6c1.112.214 1.999 1.175 2.11 2.301c.082.838-.183 1.665-.762 2.173c-1.072.94-4.524 3.476-4.524 3.476h5.3m8.701-7.058l-4.052 6.116");
}

.r3ilz2boi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.31 20.07c-4.839.424-2.916 5.732-.178 7.114c-5.173-.334-4.058-4.667-8.059-7.582c-4.179-3.045-7.04-2.857-9.647-3.637S8.78 13.061 8.78 13.061");
}

.uipahhprt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.525 10.935c4.828 3.632 5.652 3.35 10.728 2.047s5.698-.173 11.488 2.366c4.536 1.99 6.009-1.5 5.67-2.66c-.385-1.326-1.652-1.74-1.652-1.74c-.454 2.225 1.614 3.9 2.812 4.528c1.199.627 1.904.663 1.904.663c.018 1.219-.878 1.707-.878 1.707c-2.112-.643-3.716-.094-4.625.814c-1.338 1.336-1.946 2.865-3.94 3.214");
}

.wbc93aban {
  width: 5.3px;
  height: 8px;
  x: 19.756px;
  y: 29.709px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.65px;
  ry: 2.65px;
}

.zn2n_rbwd {
  cx: 18.145px;
  cy: 37.55px;
  r: 0.75px;
  fill: currentColor;
}

</style>
