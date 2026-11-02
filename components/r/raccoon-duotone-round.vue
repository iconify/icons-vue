<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="r86qnu9ba"/><path class="g0ray3b-f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:raccoon-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.g0ray3b-f {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 6c1.5 0 2.5-.2 3-1c.8-1.4 1.8-2 3-2c1.5 0 2 1 2 3c0 1.5 1 2.5 1 4v7h-2c-1 2.5-3.5 4-7 4s-6-1.5-7-4H3v-7c0-1.5 1-2.5 1-4c0-2 .5-3 2-3c1.2 0 2.2.6 3 2c.5.8 1.5 1 3 1m-3 6h.01M15 12h.01M12 18h.01M12 10c1-.7 2-1 3-1q3 0 3 3c0 1.7-.8 3-2 3h-1c-1.4 0-2.4-.8-3-2m0-3c-1-.7-2-1-3-1q-3 0-3 3c0 1.7.8 3 2 3h1c1.4 0 2.4-.8 3-2");
}

.r86qnu9ba {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M14.144 4.482C14.998 3 16.231 2.001 18 2c1.637 0 2.587.935 2.881 2.503C20.974 4.996 21 5.5 21 6c0 .261.046.521.118.772c.083.292.198.575.31.857c.313.78.572 1.516.572 2.371v7a1 1 0 0 1-1 1h-1.359a6.97 6.97 0 0 1-2.702 2.803C15.444 21.668 13.713 22 12 22s-3.444-.332-4.939-1.197A6.97 6.97 0 0 1 4.359 18H3a1 1 0 0 1-1-1v-7c0-.855.259-1.591.572-2.371c.112-.282.227-.565.31-.857A2.8 2.8 0 0 0 3 6c0-.5.026-1.004.119-1.497C3.413 2.935 4.363 2 6 2c1.769.001 3.002 1 3.856 2.482c.126.191.344.296.556.36C10.896 4.987 11.498 5 12 5s1.104-.013 1.588-.158c.212-.064.43-.169.556-.36");
}

</style>
