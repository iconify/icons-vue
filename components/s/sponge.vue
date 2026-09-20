<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="yhqgamb9x"/><path class="rpsao-bgn"/><path class="unmv3wbqe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sponge" /></template>
<style>
.rpsao-bgn {
  d: path("M43.476 28.117q.024.353.024.713v1.285a10.33 10.33 0 0 1-10.35 10.353h-18.3A10.33 10.33 0 0 1 4.5 30.115V28.83q0-.36.024-.713");
}

.unmv3wbqe {
  d: path("M20.167 33.532a1.982 1.982 0 1 1-1.983-1.983c1.095 0 1.983.888 1.983 1.983m14.257-12.448a4.93 4.93 0 1 1-9.861 0a4.93 4.93 0 1 1 9.86 0m-10.267-4.045a5.425 5.425 0 1 1-10.85 0a5.425 5.425 0 0 1 10.85 0m6.692-5.995a3.512 3.512 0 1 1-7.022 0a3.512 3.512 0 0 1 7.022 0");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yhqgamb9x {
  d: path("M24.002 15.768h9.147A10.33 10.33 0 0 1 43.5 26.12v1.286c0 5.715-4.585 10.32-10.29 10.351a1.982 1.982 0 1 0-3.93.001H14.85A10.33 10.33 0 0 1 4.5 27.406V26.12c0-5.256 3.877-9.573 8.939-10.258");
}

</style>
