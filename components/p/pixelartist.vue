<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mnw1415lw"/><circle class="ylg0u7bkh"/><circle class="g723m5-_g"/><circle class="rcb-87bbl"/><circle class="cg79r72aw"/><circle class="o78ft4byf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pixelartist" /></template>
<style>
.cg79r72aw {
  cx: 10.674px;
  cy: 29.498px;
  r: 0.75px;
  fill: currentColor;
}

.g723m5-_g {
  cx: 15.912px;
  cy: 28.925px;
  r: 0.75px;
  fill: currentColor;
}

.mnw1415lw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.555 32.77c-.543 3.383-6.76 2.132-7.706 4.338c-.59 1.372 1.568 5.132.011 5.137c-3.428.013-8.302-4.929-8.36-8.624c-.056-3.708 2.754-7.51 8.214-7.624c3.632-.076 8.915 1.878 7.84 6.773m11.422-10.935c.2 2.247-1.944 4.276-4.794 4.538s-5.334-1.343-5.554-3.588c-.108-1.11 4.003 1.356 3.672.228c-.102-.347-1.263-4.25 2.148-4.792a3.663 3.663 0 0 1 4.522 3.559m8.804-15.572a2.6 2.6 0 0 1-.028 3.638l-5.245 6.312a2.6 2.6 0 0 1-3.572.694h0a2.6 2.6 0 0 1 .028-3.639l5.245-6.311a2.6 2.6 0 0 1 3.572-.694");
}

.o78ft4byf {
  cx: 8.885px;
  cy: 31.672px;
  r: 0.75px;
  fill: currentColor;
}

.rcb-87bbl {
  cx: 13.154px;
  cy: 28.542px;
  r: 0.75px;
  fill: currentColor;
}

.ylg0u7bkh {
  cx: 18.442px;
  cy: 30.327px;
  r: 0.75px;
  fill: currentColor;
}

</style>
