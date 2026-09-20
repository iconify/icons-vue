<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path fill="url(#SVGtbHgue2z)" class="vl0iu_bqf"/><path fill="url(#SVG2XTBVb1E)" class="lon_cabor"/><path fill="url(#SVGblTbxdtN)" class="pohyjub0j"/></g><defs><linearGradient id="SVGtbHgue2z" x1="3.974" x2="20.008" y1="11.299" y2="12.71" gradientUnits="userSpaceOnUse"><stop class="w5l1ypbnv"/><stop offset=".516" class="g3550bt_p"/><stop offset="1" class="a1czyv8dn"/></linearGradient><linearGradient id="SVG2XTBVb1E" x1="4.827" x2="19.899" y1="12.304" y2="14.306" gradientUnits="userSpaceOnUse"><stop class="qhrr_fb9p"/><stop offset="1" class="n7vp-mvsk"/></linearGradient><linearGradient id="SVGblTbxdtN" x1="4" x2="10.617" y1="11.639" y2="12.984" gradientUnits="userSpaceOnUse"><stop class="gr32x8g2p"/><stop offset="1" class="sw6iq6qnh"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mobi-background" /></template>
<style>
.a1czyv8dn {
  stop-color: var(--svg-color--d9dcf8, #d9dcf8);
}

.ft5dv1b6b {
  fill: none;
}

.g3550bt_p {
  stop-color: var(--svg-color--eef3fc, #eef3fc);
}

.gr32x8g2p {
  stop-color: var(--svg-color--fcfeff, #fcfeff);
}

.lon_cabor {
  d: path("M19.752 12.854c-.292-1.569-1.956-1.961-2.75-1.961c-.696-.04-1.965.055-3.22.525l-.995-.55c1.638-1.522 3.455-1.849 4.214-1.81c3.344.216 3.227 2.62 2.751 3.796");
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.n7vp-mvsk {
  stop-color: var(--svg-color--f0f2fc, #f0f2fc);
}

.pohyjub0j {
  d: path("M7.022 14.978c-3.204-.086-3.239-2.579-2.856-3.814c.46 1.583 2.096 2.003 2.856 2.015a10 10 0 0 0 3.151-.668l1.095.61c-1.582 1.503-3.466 1.869-4.246 1.857");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qhrr_fb9p {
  stop-color: var(--svg-color--99b8ed, #99b8ed);
}

.sw6iq6qnh {
  stop-color: var(--svg-color--95b7ec, #95b7ec);
}

.vl0iu_bqf {
  d: path("M7.253 8.8c-2.47.051-3.169 2.01-3.224 2.982l.403.123c1.227-1.673 3.026-.936 3.823-.485c1.022.577 3.442 1.938 4.947 2.766s3.066 1.021 3.659 1.014c2.387-.101 2.97-2.204 3.107-3.19l-.327-.231c-.802 1.858-3.06 1.21-4.088.654c-1.05-.598-3.492-1.977-4.866-2.703c-1.373-.727-2.862-.923-3.434-.93");
}

.w5l1ypbnv {
  stop-color: var(--svg-color--d1e8f7, #d1e8f7);
}

</style>
