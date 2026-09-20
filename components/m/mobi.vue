<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGrFoJrTKa)" class="sfv7cr0vr"/><path fill="url(#SVG7WQg0dQC)" class="f-p9qtd0h"/><path fill="url(#SVGhsNbnc2d)" class="bpm7a_8ah"/><defs><linearGradient id="SVGrFoJrTKa" x1="2.971" x2="21.009" y1="11.211" y2="12.798" gradientUnits="userSpaceOnUse"><stop class="w5l1ypbnv"/><stop offset=".516" class="g3550bt_p"/><stop offset="1" class="a1czyv8dn"/></linearGradient><linearGradient id="SVG7WQg0dQC" x1="3.93" x2="20.886" y1="12.342" y2="14.595" gradientUnits="userSpaceOnUse"><stop class="qhrr_fb9p"/><stop offset="1" class="n7vp-mvsk"/></linearGradient><linearGradient id="SVGhsNbnc2d" x1="3" x2="10.444" y1="11.593" y2="13.107" gradientUnits="userSpaceOnUse"><stop class="gr32x8g2p"/><stop offset="1" class="sw6iq6qnh"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mobi" /></template>
<style>
.a1czyv8dn {
  stop-color: var(--svg-color--d9dcf8, #d9dcf8);
}

.bpm7a_8ah {
  d: path("M6.4 15.35c-3.605-.097-3.644-2.9-3.213-4.29c.517 1.78 2.358 2.253 3.213 2.267a11.3 11.3 0 0 0 3.545-.752l1.231.685c-1.779 1.693-3.898 2.104-4.776 2.09");
}

.f-p9qtd0h {
  d: path("M20.721 12.96c-.328-1.764-2.2-2.206-3.094-2.206c-.783-.045-2.21.063-3.622.59l-1.12-.618c1.843-1.711 3.888-2.08 4.742-2.036c3.76.243 3.63 2.949 3.094 4.27");
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

.n7vp-mvsk {
  stop-color: var(--svg-color--f0f2fc, #f0f2fc);
}

.qhrr_fb9p {
  stop-color: var(--svg-color--99b8ed, #99b8ed);
}

.sfv7cr0vr {
  d: path("M6.66 8.4c-2.778.057-3.565 2.261-3.627 3.354l.453.139c1.38-1.882 3.404-1.053 4.3-.546c1.15.649 3.874 2.18 5.566 3.112s3.45 1.149 4.117 1.14c2.685-.113 3.341-2.479 3.495-3.587l-.368-.261c-.902 2.09-3.442 1.362-4.6.736c-1.18-.673-3.927-2.224-5.473-3.042S7.303 8.408 6.66 8.4");
}

.sw6iq6qnh {
  stop-color: var(--svg-color--95b7ec, #95b7ec);
}

.w5l1ypbnv {
  stop-color: var(--svg-color--d1e8f7, #d1e8f7);
}

</style>
