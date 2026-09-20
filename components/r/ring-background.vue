<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVG1RxdnboI)" class="r4i437pya"/><path class="yncerq9jb"/></g><defs><linearGradient id="SVG1RxdnboI" x1="6.455" x2="10.182" y1="9.235" y2="17.982" gradientUnits="userSpaceOnUse"><stop class="la2ll6b9g"/><stop offset="1" class="e6mu-3auj"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ring-background" /></template>
<style>
.e6mu-3auj {
  stop-color: var(--svg-color--fb3777, #fb3777);
}

.ft5dv1b6b {
  fill: none;
}

.la2ll6b9g {
  stop-color: var(--svg-color--4530dd, #4530dd);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.yncerq9jb {
  fill: var(--svg-color--fff, #fff);
  d: path("M5.2 9.98a1 1 0 1 0-.4 0v4.82h.4zm7.483 1.033c.396-.634.861-1.085 1.317-1.378v3.585a1 1 0 1 0 .4 0V9.414c.32-.146.622-.214.877-.214H16.4v4.82a1 1 0 1 0 .4 0V9.2h2v4.82a1 1 0 1 0 .4 0V9.2h.8v-.4h-4.723c-.893 0-2.1.644-2.959 2.043a1.2 1.2 0 0 0-1.044 2.113c-.332.51-.765.945-1.274 1.279V10.78a1 1 0 1 0-.4 0v3.683c-.466.232-.917.337-1.274.337H4v.4h4.326c.954 0 2.373-.618 3.304-2.058a1.2 1.2 0 0 0 1.053-2.13M7.2 9.98a1 1 0 1 1 .4 0v4.82h-.4z");
}

</style>
