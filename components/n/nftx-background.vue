<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGkglSlb2n)" class="r4i437pya"/><path class="obcszxbqp"/><path class="temc1q8-w"/><path class="yc21qkb8g"/></g><defs><linearGradient id="SVGkglSlb2n" x1="14.975" x2="7.68" y1="8.233" y2="13.742" gradientUnits="userSpaceOnUse"><stop offset=".09" class="jnslgigxl"/><stop offset=".5" class="nbn9c3hhe"/><stop offset="1" class="nbn9c3hhe"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:nftx-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.jnslgigxl {
  stop-color: var(--svg-color--ff6d41, #ff6d41);
}

.nbn9c3hhe {
  stop-color: var(--svg-color--fa297f, #fa297f);
}

.obcszxbqp {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.177 15.21c.134-.185.26-.362.412-.533c-1.821.457-3.076 1.413-3.076 2.519q0 .062.006.123a7 7 0 0 0 .567-.257c1.203-.615 1.675-1.272 2.091-1.852m1.898 2.035c.364-.508.678-.945 1.568-1.4c.888-.453 1.414-.445 2.022-.435c.408.007.847.014 1.383-.106c-.653-.366-1.728-.642-2.678-.79l-1.447 1.055l-.658-.642c-.686.48-1.037.969-1.356 1.412c-.364.507-.679.945-1.568 1.399c-.624.318-1.068.41-1.488.431c.331.458.889.859 1.603 1.167q.25-.1.526-.241c1.204-.614 1.676-1.271 2.093-1.85m5.51-1.314c-.696-.011-1.484-.024-2.688.591c-1.203.615-1.674 1.272-2.091 1.852c-.364.506-.679.944-1.568 1.398l-.118.059a10.3 10.3 0 0 0 2.292.161a8 8 0 0 0 .56-.713c.363-.507.678-.945 1.567-1.399s1.415-.446 2.023-.436c.28.005.575.01.906-.026q.018-.111.017-.221c0-.455-.211-.883-.586-1.262q-.155 0-.315-.004m-2.387 3.834c1.438-.322 2.552-.95 3.031-1.722c-.41.078-.878.228-1.435.512c-.776.397-1.247.81-1.596 1.21");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.temc1q8-w {
  fill: var(--svg-color--fff, #fff);
  d: path("m12 4l-6.17 6.4L12 16.343l6.172-5.943z");
}

.yc21qkb8g {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 10.4H5.83L12 4z");
}

</style>
