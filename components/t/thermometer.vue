<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="uucp1pbjw"/><circle class="bk19aebgd"/><circle class="gyx59qb5i"/><path class="g499wjb_k"/><path class="szpd96maz"/><circle class="rek0oaboo"/><path class="fc5keubsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:thermometer" /></template>
<style>
.bk19aebgd {
  cx: 64px;
  cy: 103.6px;
  r: 22.5px;
  fill: var(--svg-color--77a3ad, #77a3ad);
}

.fc5keubsr {
  fill: none;
  stroke: var(--svg-color--77a3ad, #77a3ad);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--4px, 4px);
  d: path("M55.9 20.9h6.3m-6.1 16h6.3m-6.3 15.9h6.3m-6.3 15h6.3m-6.3 14.9h6.3");
}

.g499wjb_k {
  fill: var(--svg-color--fff, #fff);
  d: path("M64 106.7c-3.8 0-6.9-3.1-6.9-6.9V14.2c0-3.8 3.1-6.9 6.9-6.9s6.9 3.1 6.9 6.9v85.6c0 3.8-3.1 6.9-6.9 6.9");
}

.gyx59qb5i {
  cx: 64px;
  cy: 103.6px;
  r: 16.9px;
  fill: var(--svg-color--fff, #fff);
}

.rek0oaboo {
  cx: 64px;
  cy: 103.6px;
  r: 12.4px;
  fill: var(--svg-color--ed6c30, #ed6c30);
}

.szpd96maz {
  fill: var(--svg-color--ed6c30, #ed6c30);
  d: path("M64.2 99.8h-.3c-2.1 0-3.7-1.7-3.7-3.7V34.6c0-2.1 1.7-3.7 3.7-3.7h.3c2.1 0 3.7 1.7 3.7 3.7V96c0 2.1-1.7 3.8-3.7 3.8");
}

.uucp1pbjw {
  fill: var(--svg-color--77a3ad, #77a3ad);
  d: path("M64 105.1c-6.6 0-11.9-5.3-11.9-11.9V12.9C52.1 6.3 57.4 1 64 1s11.9 5.3 11.9 11.9v80.4c0 6.5-5.3 11.8-11.9 11.8");
}

</style>
