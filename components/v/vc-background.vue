<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="y9dvtof6u"/><path class="ztt4dobnn"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:vc-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.y9dvtof6u {
  fill: var(--svg-color--f40, #f40);
  d: path("M24 0H0v24h24z");
}

.ztt4dobnn {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.647 5.647a1.647 1.647 0 1 1-3.294 0a1.647 1.647 0 0 1 3.294 0m-2.602 2.899c-.15-1.318-1.835-1.873-2.81-.927a1.534 1.534 0 0 0-.273 1.854c.109.174.24.348.405.513c.34.338.581.76.701 1.223q.425 1.672-.79 2.913c-.457.462-.636 1.06-.41 1.68c.56 1.506 2.786 1.356 3.153-.188a1.6 1.6 0 0 0-.433-1.45a4 4 0 0 1-.447-.545c-.8-1.247-.579-2.739.457-3.793a1.5 1.5 0 0 0 .447-1.275zm2.41 5.647a2.956 2.956 0 0 0 .385-3.793a2.4 2.4 0 0 0-.315-.376c-.08-.09-.165-.175-.236-.269c-1.044-1.35.471-3.148 2.038-2.38a1.553 1.553 0 0 1 .405 2.56a2.977 2.977 0 0 0-.038 4.21c.584.584.73 1.356.268 2.067a1.67 1.67 0 0 1-1.694.682c-1.331-.282-1.77-1.755-.814-2.706zm-5.69-1.958a1.647 1.647 0 1 1-3.295 0a1.647 1.647 0 0 1 3.295 0m10.118 1.647a1.647 1.647 0 1 0 0-3.293a1.647 1.647 0 0 0 0 3.293m-4.236 4.471a1.647 1.647 0 1 1-3.293 0a1.647 1.647 0 0 1 3.293 0");
}

</style>
