<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVG8QFG6c9c)" class="r4i437pya"/><path class="z_f-yv6tl"/></g><defs><linearGradient id="SVG8QFG6c9c" x1="18.517" x2="6.048" y1="6.422" y2="19.606" gradientUnits="userSpaceOnUse"><stop class="el3_t9bjj"/><stop offset=".51" class="evxm7tb6m"/><stop offset=".73" class="w8-jmm_og"/><stop offset=".84" class="ibb9aqboa"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:oce-background" /></template>
<style>
.el3_t9bjj {
  stop-color: var(--svg-color--b06da7, #b06da7);
}

.evxm7tb6m {
  stop-color: var(--svg-color--a5a5d1, #a5a5d1);
}

.ft5dv1b6b {
  fill: none;
}

.ibb9aqboa {
  stop-color: var(--svg-color--4e9dd7, #4e9dd7);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.w8-jmm_og {
  stop-color: var(--svg-color--92d1f4, #92d1f4);
}

.z_f-yv6tl {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.273 4.61a4.54 4.54 0 0 0-4.546 0L6.744 6.333a4.55 4.55 0 0 0-2.272 3.938v.155a4.14 4.14 0 0 1 2.07-3.58l2.715-1.572a4.13 4.13 0 0 1 4.131 0l2.72 1.571a4.09 4.09 0 0 1 2.009 3.581v3.143a4.09 4.09 0 0 1-2.01 3.58l-2.719 1.572a4.13 4.13 0 0 1-4.131 0l-2.72-1.571a4.14 4.14 0 0 1-2.065-3.58v.155a4.55 4.55 0 0 0 2.272 3.938l2.983 1.727a4.54 4.54 0 0 0 4.546 0l2.983-1.727a4.54 4.54 0 0 0 2.273-3.938V10.27a4.54 4.54 0 0 0-2.273-3.938l-2.983-1.727zM9.596 5.975a3.54 3.54 0 0 1 3.613 0l2.377 1.412a3.7 3.7 0 0 1 1.68 2.23a3.3 3.3 0 0 0-1.473-1.722L13.59 6.643a3.41 3.41 0 0 0-3.355 0L8.029 7.895a3.28 3.28 0 0 0-1.675 2.851v2.503c0 1.176.64 2.263 1.675 2.852l2.207 1.251a3.4 3.4 0 0 0 3.355 0l2.202-1.251a3.3 3.3 0 0 0 1.472-1.718a3.7 3.7 0 0 1-1.68 2.226L13.21 18.02a3.54 3.54 0 0 1-3.613 0L7.22 16.61a3.72 3.72 0 0 1-1.807-3.2v-2.823A3.72 3.72 0 0 1 7.22 7.382L9.596 5.97zm3.143 1.915a2.69 2.69 0 0 0-2.612 0l-1.722.96a2.54 2.54 0 0 0-1.19 1.444a2.92 2.92 0 0 1 1.383-1.943l1.896-1.11a2.85 2.85 0 0 1 2.89 0l1.896 1.11a2.92 2.92 0 0 1 1.425 2.536v2.221a2.92 2.92 0 0 1-1.425 2.536l-1.897 1.11a2.85 2.85 0 0 1-2.889 0l-1.896-1.11a2.92 2.92 0 0 1-1.383-1.948a2.54 2.54 0 0 0 1.19 1.45l1.722.96a2.69 2.69 0 0 0 2.612 0l1.717-.96a2.51 2.51 0 0 0 1.308-2.188v-1.92c0-.904-.498-1.741-1.308-2.188z");
}

</style>
