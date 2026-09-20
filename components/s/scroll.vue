<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="hj-3oobff"/><path class="g20rdc13i"/><path class="fwbye61dv"/><ellipse class="vzag1q8kq"/><ellipse class="hzdvv0peh"/><path class="k4-puccbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:scroll" /></template>
<style>
.fwbye61dv {
  fill: var(--svg-color--b79f98, #b79f98);
  d: path("M108.13 22.07H19.87c-5.45 0-7.91-4.46-7.91-9.91s2.46-9.91 7.91-9.91h88.25c5.45 0 7.91 4.46 7.91 9.91c.01 5.44-2.45 9.91-7.9 9.91m0 103.69H19.87c-5.45 0-7.91-4.46-7.91-9.91s2.46-9.91 7.91-9.91h88.25c5.45 0 7.91 4.46 7.91 9.91c.01 5.45-2.45 9.91-7.9 9.91");
}

.g20rdc13i {
  fill: var(--svg-color--d1c1bd, #d1c1bd);
  d: path("M19.87 12.15h8.52v105.6h-8.52zm87.65 0h8.52v105.6h-8.52z");
}

.hj-3oobff {
  fill: var(--svg-color--efebe9, #efebe9);
  d: path("M112.98 12.15H22.94c-1.69 0-3.06 1.29-3.06 2.89v99.82c0 1.59 1.37 2.89 3.06 2.89h90.04c1.69 0 3.06-1.29 3.06-2.89V15.04c0-1.6-1.37-2.89-3.06-2.89");
}

.hzdvv0peh {
  cx: 108.87px;
  cy: 12.15px;
  fill: var(--svg-color--8d6e63, #8d6e63);
  rx: 5.28px;
  ry: 8.07px;
}

.k4-puccbg {
  fill: var(--svg-color--c1aeaa, #c1aeaa);
  d: path("M98.21 36.93h-60.5a2.5 2.5 0 0 1 0-5h60.5a2.5 2.5 0 0 1 0 5m0 15.26h-60.5a2.5 2.5 0 0 1 0-5h60.5a2.5 2.5 0 0 1 0 5m0 15.26h-60.5a2.5 2.5 0 0 1 0-5h60.5a2.5 2.5 0 0 1 0 5m0 15.26h-60.5a2.5 2.5 0 0 1 0-5h60.5a2.5 2.5 0 0 1 0 5M63.58 97.97H37.71a2.5 2.5 0 0 1 0-5h25.88c1.38 0 2.5 1.12 2.5 2.5s-1.13 2.5-2.51 2.5");
}

.vzag1q8kq {
  cx: 108.87px;
  cy: 115.85px;
  fill: var(--svg-color--8d6e63, #8d6e63);
  rx: 5.28px;
  ry: 8.07px;
}

</style>
