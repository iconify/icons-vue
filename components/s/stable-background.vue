<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGFy5oadNQ)" class="r4i437pya"/><path class="ezf9jobjq"/></g><defs><linearGradient id="SVGFy5oadNQ" x1="24" x2="0" y1="0" y2="24" gradientUnits="userSpaceOnUse"><stop class="ix8l8rbov"/><stop offset="1" class="w__6rxf6s"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:stable-background" /></template>
<style>
.ezf9jobjq {
  fill: var(--svg-color--e8fbf7, #e8fbf7);
  d: path("M11.99 12.734c.66-.4 1.602-.954 2.342-.954c1.186 0 2.176.839 2.176 2.433c0 2.543-3.022 4.887-7.294 3.866a.023.023 0 0 0-.028.021v1.375q0 .016.015.021a8 8 0 0 0 1.856.449c5.004.588 9.328-3.587 8.916-8.609a7.85 7.85 0 0 0-1.391-3.884c-.006-.009-.017-.014-.031-.006l-6.557 3.79c-.745.425-1.602.957-2.341.957c-1.185 0-2.176-.84-2.176-2.433c0-2.543 3.023-4.887 7.294-3.866a.022.022 0 0 0 .028-.022V4.52a.02.02 0 0 0-.014-.021a8 8 0 0 0-9.388 12.019c.007.01.02.012.03.007z");
}

.ft5dv1b6b {
  fill: none;
}

.ix8l8rbov {
  stop-color: var(--svg-color--011f1e, #011f1e);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.w__6rxf6s {
  stop-color: var(--svg-color--044030, #044030);
}

</style>
