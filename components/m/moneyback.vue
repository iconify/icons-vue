<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="ozot8mbxw"/><path class="m3kstz9mi"/><path class="b8-dxjbrh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:moneyback" /></template>
<style>
.b8-dxjbrh {
  d: path("M16.348 17.24c.032.146 10.577 1.657 11.723-7.875m5.709 6.701s-11.905-.498-11.905 7.827");
}

.m3kstz9mi {
  d: path("M21.875 23.893a6.768 6.768 0 1 1-13.536 0a6.768 6.768 0 0 1 13.536 0m17.689-13.61a5.783 5.783 0 1 1-11.566 0a5.783 5.783 0 0 1 11.566 0m.096 27.434a5.783 5.783 0 1 1-11.566 0a5.783 5.783 0 0 1 11.567 0");
}

.ozot8mbxw {
  d: path("M32.655 32.065c-.032.146-10.78.584-10.78-8.172m-5.647 6.663s10.716-1.436 11.906 7.827");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
