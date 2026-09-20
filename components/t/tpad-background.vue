<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path fill="url(#SVGFsBTWdVW)" class="yzhukmb5n"/></g><defs><linearGradient id="SVGFsBTWdVW" x1="11.711" x2="17.593" y1="16.036" y2="14.065" gradientUnits="userSpaceOnUse"><stop class="s-hug556i"/><stop offset="1" class="wtn33i8_k"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:tpad-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.s-hug556i {
  stop-color: var(--svg-color--fc01c2, #fc01c2);
}

.wtn33i8_k {
  stop-color: var(--svg-color--6d138e, #6d138e);
}

.yzhukmb5n {
  d: path("m11.889 20l.009-16l-6.565 3.049l1.791 1.053l3.543-1.618v12.8c.2.125.404.24.608.356zm1.444-.711L12.107 20V4l6.56 3.049l-1.77 1.071l-3.564-1.676zm-8-11.591c.285.169.587.338.89.506c.301.17.604.338.888.507v6.391l3.111 1.85v2l-4.889-2.85zm12.445.506c.302-.168.604-.337.889-.506v8.404q-1.223.715-2.445 1.45l-2.444 1.444V16.95c.533-.311 1.044-.618 1.555-.924a73 73 0 0 1 1.556-.925v-6.39c.284-.17.587-.339.889-.508");
}

</style>
