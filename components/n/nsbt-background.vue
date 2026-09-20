<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="b1dz01b5o"/><path clip-rule="evenodd" class="rzkmpz-5m"/><path class="uyg_yds8b"/><path class="v3l9i2bsd"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:nsbt-background" /></template>
<style>
.b1dz01b5o {
  fill: var(--svg-color--6a53f3, #6a53f3);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.rzkmpz-5m {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("m20 12l-8-8l-8 8l8 8zM9.778 15.555h-.89v-3.11H7.112v-.89H8.89v-3.11h.889l4.444 5.582V8.445h.889v3.11h1.778v.89h-1.78v3.11h-.889l-4.444-5.55z");
}

.uyg_yds8b {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.778 15.555h-.89v-3.11H7.112v-.89H8.89v-.794a4 4 0 0 0-.796-.094C6.093 10.667 4 12 4 12l8 8l7.978-7.973c-.267.15-1.818.862-4.13.862q-.36-.001-.737-.055v2.721h-.889l-3.295-4.116c-.396-.158-.78-.306-1.15-.429z");
}

.v3l9i2bsd {
  fill: var(--svg-color--fff, #fff);
  d: path("m12.739 12.162l1.483 1.864v-1.377c-.489-.129-.987-.3-1.483-.487");
}

</style>
