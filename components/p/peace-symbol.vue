<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="paa3h1b7a"/><path class="e8_2-m9cn"/><path class="bnzytr-lx"/><path class="k21p6x6nv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:peace-symbol" /></template>
<style>
.bnzytr-lx {
  fill: var(--svg-color--fafafa, #fafafa);
  d: path("M40.16 12.86c0-2.3-1.6-3-10.8-2.7c-7.7.3-11.5 1.2-13.8 4s-2.9 8.5-3 15.3c0 4.8 0 9.3 2.5 9.3c3.4 0 3.4-7.9 6.2-12.3c5.4-8.7 18.9-10.6 18.9-13.6");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.e8_2-m9cn {
  fill: var(--svg-color--ab47bc, #ab47bc);
  d: path("M110.16 3.96h-98.2a7.555 7.555 0 0 0-7.5 7.5v97.9c-.01 4.14 3.34 7.49 7.48 7.5h98.12c4.14.01 7.49-3.34 7.5-7.48V11.46c.09-4.05-3.13-7.41-7.18-7.5z");
}

.k21p6x6nv {
  fill: var(--svg-color--fff, #fff);
  d: path("M64.46 15.96c-26.51 0-48 21.49-48 48s21.49 48 48 48s48-21.49 48-48s-21.49-48-48-48m40 48c0 9.22-3.17 18.16-9 25.3l-27-27v-38.1c20.44 2.06 36 19.26 36 39.8m-44 39.8a40.17 40.17 0 0 1-21.3-8.8l21.3-21.3zm8-30.1l21.3 21.3a40.17 40.17 0 0 1-21.3 8.8zm-8-49.5v38.1l-27 27c-13.97-17.11-11.43-42.31 5.68-56.28c6.09-4.97 13.5-8.03 21.32-8.82");
}

.paa3h1b7a {
  fill: var(--svg-color--8e24aa, #8e24aa);
  d: path("M116.46 3.96h-104c-4.42 0-8 3.58-8 8v104c0 4.42 3.58 8 8 8h104c4.42 0 8-3.58 8-8v-104c0-4.42-3.58-8-8-8");
}

</style>
