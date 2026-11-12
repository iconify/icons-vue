<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="gshkn9qqt"/><path class="ud0vn3b7v"/><path class="thq5dxb7d"/><path class="wvjt8gthe"/><path class="frg8avblm"/><path class="wurlbwzqw"/><path class="mm4sswb_u"/><path class="gqr5orb3s"/><path class="upr0i9feh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:spedometer-low-line-duotone" /></template>
<style>
.frg8avblm {
  d: path("M5 5L6.5 6.5");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.gqr5orb3s {
  d: path("M12 4.00021L12 2.00021");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.gshkn9qqt {
  d: path("M22 12C22 17.5228 17.5228 22 12 22C6.47715 22 2 17.5228 2 12C2 6.47715 6.47715 2 12 2C17.5228 2 22 6.47715 22 12Z");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mm4sswb_u {
  d: path("M19.9998 12L21.9998 12");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.thq5dxb7d {
  d: path("M19 5L17.5 6.5");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ud0vn3b7v {
  d: path("M19 19L17.5 17.5");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.upr0i9feh {
  d: path("M13.7783 14.3638C14.9499 13.1923 14.9499 11.2928 13.7783 10.1212C12.6068 8.94963 10.7073 8.94963 9.5357 10.1212C9.09005 10.5669 8.77881 11.492 8.56421 12.4673C8.24329 13.9258 8.08283 14.6551 8.66363 15.2359C9.24444 15.8167 9.9737 15.6563 11.4322 15.3353C12.4076 15.1207 13.3327 14.8095 13.7783 14.3638Z");
}

.wurlbwzqw {
  d: path("M2 12H4");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.wvjt8gthe {
  d: path("M5 19L6.5 17.5");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
