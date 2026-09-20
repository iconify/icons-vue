<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":196};
const content = `<circle class="vpw17pnds"/><circle class="nphjy9b0g"/><path class="t5kdav0eq"/><path class="kgeb5q4nf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:wearos" /></template>
<style>
.kgeb5q4nf {
  fill: var(--svg-color--0085f7, #0085f7);
  d: path("M89.76 195.254c-10.355 0-20.22-5.996-24.69-16.024L2.336 38.282c-6.05-13.627.054-29.596 13.68-35.646s29.596.054 35.646 13.68l62.734 140.948c6.05 13.626-.054 29.596-13.68 35.646a27 27 0 0 1-10.956 2.344");
}

.nphjy9b0g {
  cx: 231.199px;
  cy: 25.201px;
  r: 24.799px;
  fill: var(--svg-color--ff4131, #ff4131);
}

.t5kdav0eq {
  fill: var(--svg-color--ffbc00, #ffbc00);
  d: path("M166.502 195.635c-9.483 0-18.586-5.505-22.673-14.716L78.805 34.902c-5.56-12.536.055-27.197 12.59-32.757c12.537-5.56 27.198.055 32.758 12.59l65.023 146.018c5.56 12.536-.054 27.197-12.59 32.757c-3.27 1.471-6.704 2.125-10.084 2.125");
}

.vpw17pnds {
  cx: 201.603px;
  cy: 79.759px;
  r: 26.544px;
  fill: var(--svg-color--00a94b, #00a94b);
}

</style>
