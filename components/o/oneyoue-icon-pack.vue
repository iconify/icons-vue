<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="moq63xbrp"/><path class="mwl8--15p"/><circle class="wrfn47edt"/><path class="ji5ualnou"/><circle class="y9lcg8bnu"/><path class="bqq8tac6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:oneyoue-icon-pack" /></template>
<style>
.bqq8tac6m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.422 22.43v-6.562l5.624 6.562v-6.562m3.602 3.281h3.618m.931 3.281h-4.549v-6.562h4.549");
}

.ji5ualnou {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.11 25.57v3.75a2.812 2.812 0 1 0 5.624 0v-3.75");
}

.moq63xbrp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.83 43.862c-3.25-2.727-7.11 1.182-9.506-4.247c-1.451-3.985-6.748-2.53-6.11-8.43C5.951 27.008.636 25.62 4.14 20.83c2.726-3.25-1.183-7.11 4.246-9.506c3.985-1.451 2.53-6.748 8.43-6.11C20.992 5.952 22.38.637 27.17 4.14c3.25 2.726 7.11-1.182 9.506 4.246c1.451 3.985 6.748 2.53 6.11 8.43c-.737 4.177 4.578 5.566 1.075 10.355c-2.726 3.25 1.182 7.11-4.246 9.506c-3.985 1.451-2.53 6.748-8.43 6.11c-4.177-.737-5.566 4.578-10.355 1.076Z");
}

.mwl8--15p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m18.358 25.57l-2.812 3.281l-2.812-3.281m2.812 6.562v-3.281");
}

.wrfn47edt {
  cx: 23.924px;
  cy: 28.851px;
  r: 3.281px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.y9lcg8bnu {
  cx: 15.546px;
  cy: 19.149px;
  r: 3.281px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
