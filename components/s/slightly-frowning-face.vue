<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="rj28-ab-a"/><g class="n1mjunbsu"><ellipse class="qh31ndt_k"/><path class="aqyy8fr6z"/></g><path class="tj4alhj_c"/><path class="i59fa7bor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:slightly-frowning-face" /></template>
<style>
.aqyy8fr6z {
  d: path("M49.547 24.669c0 5.387-2.907 9.752-6.503 9.752s-6.515-4.365-6.515-9.752c0-5.384 2.919-9.748 6.515-9.748s6.503 4.364 6.503 9.748");
}

.i59fa7bor {
  fill: var(--svg-color--633d19, #633d19);
  d: path("M44.45 51.936h-1.864c-.095 0-.162-.035-.248-.049c-.095-.014-.185-.018-.279-.058a1.2 1.2 0 0 1-.405-.261c-.023-.022-.055-.026-.079-.052c-4.492-4.378-10.377-5.377-15.982-2.494c-3.01 1.548-2.762 2.913-5.983 2.913c-1.318 0-1.81-1.528-1.015-2.442c7.27-8.387 19.598-8.387 26.867 0c.794.914.306 2.443-1.012 2.443");
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.qh31ndt_k {
  cx: 21.02px;
  cy: 24.669px;
  rx: 6.51px;
  ry: 9.752px;
}

.rj28-ab-a {
  fill: var(--svg-color--ffbf67, #ffbf67);
  d: path("M64.005 32.004c0 17.676-14.323 32.004-32.003 32.004S0 49.685 0 32.004C0 14.33 14.323 0 32.002 0c17.676 0 32.003 14.327 32.003 32.004");
}

.tj4alhj_c {
  fill: var(--svg-color--25333a, #25333a);
  d: path("M25.23 24.669c0 2.822-1.884 5.108-4.209 5.108c-2.329 0-4.213-2.286-4.213-5.108c0-2.815 1.884-5.106 4.213-5.106c2.325-.001 4.209 2.291 4.209 5.106m22.03 0c0 2.822-1.888 5.108-4.213 5.108c-2.329 0-4.213-2.286-4.213-5.108c0-2.815 1.884-5.106 4.213-5.106c2.325-.001 4.213 2.291 4.213 5.106");
}

</style>
