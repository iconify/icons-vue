<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="a9tdekb7u"/><path class="c89hekb9t"/><path class="taq98qbic"/><circle class="d5oa8-ndv"/><linearGradient id="SVGvwClFcCe" x1="97.278" x2="97.278" y1="104.769" y2="22.712" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="lmwksq2ex"/></linearGradient><path fill="url(#SVGvwClFcCe)" class="pprm2cbhc"/><g class="n1mjunbsu"><path class="ic-ybbbxu"/><path class="uufmllbxi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:mobile-phone-with-arrow" /></template>
<style>
.a9tdekb7u {
  fill: var(--svg-color--ed6c30, #ed6c30);
  d: path("M61.01 64L29.68 86.97V72.64H.44V55.5h29.24V41.03z");
}

.c89hekb9t {
  fill: var(--svg-color--006ca2, #006ca2);
  d: path("M121.74 6.34c-4.24-1.9-16.62-3.11-24.47-3.11c-7.84 0-20.23 1.21-24.46 3.11C68.67 8.2 67 11.87 67 15.33v97.34c0 3.46 1.67 7.13 5.82 8.99c4.23 1.9 16.62 3.11 24.46 3.11c7.85 0 20.23-1.21 24.47-3.11c4.15-1.86 5.81-5.53 5.81-8.99V15.33c-.01-3.46-1.67-7.13-5.82-8.99");
}

.d5oa8-ndv {
  cx: 117.17px;
  cy: 10.49px;
  r: 1.99px;
  fill: var(--svg-color--fff, #fff);
}

.ic-ybbbxu {
  d: path("M81.65 108.93v.7l-1.53-1.11l1.53-1.12v.7h.88c1.72 0 2.83.51 2.83 1.99c0 1.49-1.11 2-2.83 2h-1.98v-.83h1.98c1.46 0 2-.32 2-1.17c0-.84-.53-1.16-2-1.16zm18.54 2.88h-5.74v-2.9l2.87-1.21l2.87 1.21zm-4.91-.83h4.08v-1.52l-2.03-.86l-2.04.86v1.52zm18.55.83h-4.8v-3.04h4.8zm-3.97-.83H113v-1.37h-3.14z");
}

.lmwksq2ex {
  stop-color: var(--svg-color--00a0d6, #00a0d6);
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.pprm2cbhc {
  d: path("M72.49 22.71h49.57v82.06H72.49z");
}

.taq98qbic {
  fill: var(--svg-color--fff, #fff);
  d: path("M102.85 10.75H91.72c-.58 0-1.04-.46-1.04-1.04c0-.57.46-1.04 1.04-1.04h11.13a1.04 1.04 0 1 1 0 2.08");
}

.uufmllbxi {
  d: path("M115.19 110.09h-.83v-1.78h-3.55v-.83h4.38z");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

</style>
