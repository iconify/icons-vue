<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<ellipse transform="rotate(-6.21 96.694 75.04)" class="b_flbr3bd"/><ellipse transform="rotate(-3.42 45.535 24.492)" class="gln8vvizs"/><ellipse transform="rotate(-83.13 62.97 30.568)" class="re2hhyblm"/><ellipse transform="rotate(-13.24 27.208 27.783)" class="pjwq5-woe"/><path class="dmarctbce"/><ellipse transform="rotate(-30 12.91 40.94)" class="i5wpkhbus"/><ellipse transform="rotate(-30 79.07 82.367)" class="j87v7sbts"/><ellipse transform="rotate(-35.35 67.236 97.302)" class="sd2wu0zgb"/><ellipse transform="rotate(-3.53 114.851 78.25)" class="wl2eyfbur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:paw-prints" /></template>
<style>
.b_flbr3bd {
  cx: 96.65px;
  cy: 75.06px;
  fill: var(--svg-color--176bc6, #176bc6);
  rx: 7.46px;
  ry: 10.19px;
}

.dmarctbce {
  fill: var(--svg-color--176bc6, #176bc6);
  d: path("M89.66 94.36c15.11-8.45 32.4 3.47 30.13 12.58c-2.44 9.76-11.73 4.5-18.68 7.04c-4.27 1.56-10.79 10.32-18.3 4.97c-6.55-4.67-3.01-19.08 6.85-24.59m-51.5-53.95c10.8-2.83 25.86 5.56 24.14 15.13c-1.62 9.01-14.14 5.08-19.22 6.97c-6.62 2.46-14.92 9.71-19.64 2.46c-5.32-8.19 5.24-22.07 14.72-24.56");
}

.gln8vvizs {
  cx: 45.49px;
  cy: 24.46px;
  fill: var(--svg-color--176bc6, #176bc6);
  rx: 7.7px;
  ry: 10.06px;
}

.i5wpkhbus {
  cx: 12.91px;
  cy: 40.93px;
  fill: var(--svg-color--176bc6, #176bc6);
  rx: 7.71px;
  ry: 9.95px;
}

.j87v7sbts {
  cx: 79.08px;
  cy: 82.36px;
  fill: var(--svg-color--176bc6, #176bc6);
  rx: 8.01px;
  ry: 10.19px;
}

.pjwq5-woe {
  cx: 27.21px;
  cy: 27.8px;
  fill: var(--svg-color--176bc6, #176bc6);
  rx: 7.83px;
  ry: 10.74px;
}

.re2hhyblm {
  cx: 62.97px;
  cy: 30.56px;
  fill: var(--svg-color--176bc6, #176bc6);
  rx: 9.6px;
  ry: 7.7px;
}

.sd2wu0zgb {
  cx: 67.22px;
  cy: 97.3px;
  fill: var(--svg-color--176bc6, #176bc6);
  rx: 7.46px;
  ry: 10.19px;
}

.wl2eyfbur {
  cx: 115.06px;
  cy: 78.32px;
  fill: var(--svg-color--176bc6, #176bc6);
  rx: 7.43px;
  ry: 9.46px;
}

</style>
