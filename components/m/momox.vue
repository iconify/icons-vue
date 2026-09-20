<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ajr5-cclw"/><path class="yi_9chbzu"/><g class="y9tr6bcfx"><path class="q2us30bjh"/><path class="m82e3kg5m"/></g><path class="fk7kwsd2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:momox" /></template>
<style>
.ajr5-cclw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.113 17.03s4.442-4.831 10.974-4.954s12.542 5.871 12.41 11.68c-.13 5.81-4.572 12.17-12.28 12.17s-10.974-4.832-10.974-4.832s-3.135 2.263-6.401 2.263c-1.794 0-4.77-1.076-6.794-2.966c-1.66-1.55-2.577-3.659-2.547-6.084c.065-5.382 4.397-8.561 7.999-9.234c1.522-.285 3.582-.07 4.704.284c1.669.527 2.909 1.673 2.909 1.673m21.038 4.221l-4.072 5.498m4.072 0l-4.072-5.498");
}

.fk7kwsd2s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.935 23.338c0-1.12.916-2.036 2.036-2.036s2.036.916 2.036 2.036v1.324c0 1.12-.916 2.036-2.036 2.036s-2.036-.916-2.036-2.036z");
}

.m82e3kg5m {
  d: path("M26.432 23.287c0-1.12.916-2.036 2.036-2.036s2.036.917 2.036 2.036v3.36");
}

.q2us30bjh {
  d: path("M22.36 23.287c0-1.12.916-2.036 2.036-2.036s2.036.917 2.036 2.036v3.36m-4.072-5.396v5.498");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yi_9chbzu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.175 23.287c0-1.12.916-2.036 2.036-2.036s2.036.917 2.036 2.036v3.36m-4.072-5.396v5.498m4.072-3.462c0-1.12.916-2.036 2.036-2.036s2.036.917 2.036 2.036v3.36m1.476-3.309c0-1.12.917-2.036 2.036-2.036s2.037.916 2.037 2.036v1.324c0 1.12-.917 2.036-2.037 2.036s-2.036-.916-2.036-2.036z");
}

</style>
