<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><radialGradient id="SVGQ9IGmIko" cx="64" cy="-2344" r="56.96" fx="64" fy="-2344" gradientTransform="matrix(1 0 0 -1 0 -2280)" gradientUnits="userSpaceOnUse"><stop offset=".12" class="so5rw4ujv"/><stop offset=".32" class="fc2c7dbsg"/><stop offset=".48" class="qg_ueccaj"/><stop offset=".62" class="fnjfcdbdr"/><stop offset=".76" class="rjhiaxsgo"/><stop offset=".88" class="whqap_bgb"/><stop offset="1" class="rn92qobhi"/></radialGradient></defs><g class="wj4kgr0on"><path fill="url(#SVGQ9IGmIko)" class="uuo0vn6ns"/><path class="gusbagbtz"/></g><path class="k9o0q-40f"/><path class="g3an3pnrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:pouting-face" /></template>
<style>
.fc2c7dbsg {
  stop-color: var(--svg-color--fac340, #fac340);
}

.fnjfcdbdr {
  stop-color: var(--svg-color--fba931, #fba931);
}

.g3an3pnrj {
  fill: var(--svg-color--896024, #896024);
  d: path("M45.41 65.42c-1.16-.8-2.88-.55-4.01 1.07s-.75 3.32.41 4.13c1.16.8 2.88.55 4.01-1.07s.75-3.32-.41-4.13m36.37 0c-1.16-.8-2.88-.55-4.01 1.07c-1.12 1.62-.75 3.32.41 4.13c1.16.8 2.88.55 4.01-1.07c1.12-1.62.75-3.32-.41-4.13");
}

.gusbagbtz {
  fill: var(--svg-color--d84213, #d84213);
  d: path("M111.89 30.77C117.22 39.37 120 49.61 120 61c0 16.9-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5c-18.06 0-37.04-7.35-48.18-22.94C24.58 111.62 44.81 119.9 64 119.9c15.4 0 29.8-5.2 40.4-14.5C115.9 95.2 122 80.9 122 64c0-12.74-3.47-24.06-10.11-33.23");
}

.k9o0q-40f {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M85.48 104.22c-.38-.15-.72-.38-1-.69c-4.65-5.26-12.29-8.71-20.48-8.71s-15.83 3.46-20.48 8.71c-.28.31-.62.55-1 .69c-.84.31-1.79.13-2.46-.46c-.65-.58-.88-1.47-.55-2.33C42.84 92.89 52.75 86.17 64 86.17s21.15 6.71 24.49 15.26c.34.85.1 1.75-.55 2.33c-.67.59-1.63.77-2.46.46M56.62 65.83c-2.51-3.15-12.83-9.22-16.56-10.96c-1.39-.64-2.83-1.15-4.31-1.53a3 3 0 0 0-.84-.11c-1.5 0-2.77 1.04-3.12 2.54c-.35 1.51.37 2.99 1.87 3.71c1.75.86 4.82 2.49 8 4.3c-2.51 1.5-4.21 4.31-4.21 7.53v1.63c0 4.8 3.76 8.69 8.39 8.69s8.39-3.89 8.39-8.69v-1.82c1.18-.07 2.26-.78 2.79-1.87c.55-1.13.39-2.41-.4-3.41ZM96.2 55.76c-.35-1.5-1.62-2.54-3.12-2.54c-.28 0-.56.03-.84.11c-1.48.38-2.92.89-4.31 1.53c-3.73 1.75-14.05 7.81-16.56 10.96c-.79 1.01-.95 2.28-.4 3.41a3.38 3.38 0 0 0 2.81 1.87v1.82c0 4.8 3.76 8.69 8.39 8.69s8.39-3.89 8.39-8.69v-1.63c0-3.22-1.7-6.03-4.22-7.53c3.18-1.8 6.24-3.43 8-4.29c1.5-.73 2.21-2.2 1.87-3.71Z");
}

.qg_ueccaj {
  stop-color: var(--svg-color--fab93a, #fab93a);
}

.rjhiaxsgo {
  stop-color: var(--svg-color--fc9124, #fc9124);
}

.rn92qobhi {
  stop-color: var(--svg-color--ff5100, #ff5100);
}

.so5rw4ujv {
  stop-color: var(--svg-color--fac742, #fac742);
}

.uuo0vn6ns {
  d: path("M64 119.9c-27.9 0-58-17.5-58-55.9S36.1 8.1 64 8.1c15.5 0 29.8 5.1 40.4 14.4C115.9 32.7 122 47.1 122 64s-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5");
}

.whqap_bgb {
  stop-color: var(--svg-color--fd7313, #fd7313);
}

.wj4kgr0on {
  stroke-width: var(--svg-stroke-width--0px, 0px);
}

</style>
