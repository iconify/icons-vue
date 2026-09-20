<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<g class="j71m3fb1u"><path class="bzayrfm6l"/><path class="m9z_dibzx"/><path class="tg3p-eezr"/><path class="uqxv4ub4i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:male-sign" /></template>
<style>
.bzayrfm6l {
  d: path("M119.175 9.018v41.26h-16.42V9.018z");
}

.j71m3fb1u {
  fill: var(--svg-color--fcc21b, #fcc21b);
}

.m9z_dibzx {
  d: path("M119.278 25.432h-41.26V9.012h41.26z");
}

.tg3p-eezr {
  d: path("M110.389 29.414L78.873 60.93l-11.61-11.61l31.515-31.516z");
}

.uqxv4ub4i {
  d: path("M77.49 50.7c-15.96-15.96-41.84-15.96-57.8 0s-15.96 41.84 0 57.8s41.84 15.96 57.8 0s15.96-41.84 0-57.8M31.61 96.58c-9.38-9.38-9.38-24.58 0-33.96s24.58-9.38 33.96 0s9.38 24.58 0 33.96c-9.37 9.38-24.58 9.38-33.96 0");
}

</style>
