<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kg1547-wy"/><path class="k-z4unb1m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pos-paid-out" /></template>
<style>
.k-z4unb1m {
  d: path("M14.663 11.188q.087-.338.087-.688q0-.135-.013-.27q-.013-.134-.04-.266q-.026-.133-.065-.262q-.04-.13-.091-.254q-.052-.125-.116-.244q-.063-.119-.138-.232q-.076-.112-.161-.217q-.086-.104-.181-.2q-.096-.095-.2-.181t-.217-.161t-.232-.138q-.119-.064-.244-.116q-.124-.051-.254-.091q-.129-.039-.262-.065q-.132-.027-.266-.04q-.135-.013-.27-.013t-.27.013t-.266.04q-.133.026-.262.065q-.13.04-.254.091q-.125.052-.244.116q-.119.063-.232.138q-.112.076-.217.161q-.104.086-.2.181q-.095.096-.181.2t-.161.217t-.138.232q-.064.119-.116.244q-.051.124-.091.254q-.039.129-.065.262q-.027.132-.04.266q-.013.135-.013.27t.013.27t.04.266q.026.133.065.262q.04.13.091.254q.052.125.116.244q.063.119.138.232q.076.112.161.217q.086.104.181.2q.096.095.2.181t.217.161t.232.138q.119.064.244.116q.124.051.254.091q.129.039.261.065q.133.027.267.04q.135.013.27.013q.235 0 .466-.04M6 10.5h.01m11.99 0h.01M15.25 14h5.5v7.75L19.5 21l-1.5.75l-1.5-.75l-1.25.75Zm1.5 2.5h2.5m-2.5 2.25h2.5");
}

.kg1547-wy {
  d: path("M12.4 17H2.5V4h19v7.2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
