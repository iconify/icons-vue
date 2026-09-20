<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGOrPuUU8x)" class="bmm5upbqp"/><path fill="url(#SVGFXJP0brH)" class="b81pzbc_t"/><path fill="url(#SVG8lTZ1d2U)" class="y89swwoop"/><path fill="url(#SVGZu17IcTc)" class="jmnik472b"/><defs><linearGradient id="SVGOrPuUU8x" x1="11.465" x2="16.026" y1="11.426" y2="18.817" gradientUnits="userSpaceOnUse"><stop class="ih1wjzr2h"/><stop offset="1" class="lq9lvnbri"/></linearGradient><linearGradient id="SVGFXJP0brH" x1="11.465" x2="16.026" y1="11.423" y2="18.814" gradientUnits="userSpaceOnUse"><stop class="ih1wjzr2h"/><stop offset="1" class="lq9lvnbri"/></linearGradient><linearGradient id="SVG8lTZ1d2U" x1="11.464" x2="16.025" y1="11.424" y2="18.814" gradientUnits="userSpaceOnUse"><stop class="ih1wjzr2h"/><stop offset="1" class="lq9lvnbri"/></linearGradient><linearGradient id="SVGZu17IcTc" x1="11.465" x2="16.026" y1="11.425" y2="18.815" gradientUnits="userSpaceOnUse"><stop class="ih1wjzr2h"/><stop offset="1" class="lq9lvnbri"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:paid" /></template>
<style>
.b81pzbc_t {
  d: path("M13.2 4.2h1.2a2.4 2.4 0 0 1 2.4 2.4v4.8a2.4 2.4 0 0 1-2.4 2.4h-1.2a2.4 2.4 0 0 1-2.4-2.4H9.6a3.6 3.6 0 0 0 3.6 3.6h1.2a3.6 3.6 0 0 0 3.6-3.6V6.6A3.6 3.6 0 0 0 14.4 3h-1.2a3.6 3.6 0 0 0-3.12 1.8h1.53c.42-.372.984-.6 1.59-.6");
}

.bmm5upbqp {
  d: path("M13.8 9.002v1.2l-.006.192l.426 2.04a3.58 3.58 0 0 0 .78-2.232v-1.2a3.6 3.6 0 0 0-3.6-3.6H6.6a3.6 3.6 0 0 0-3.6 3.6v1.2a3.6 3.6 0 0 0 1.8 3.12v-1.53c-.372-.42-.6-.984-.6-1.59v-1.2a2.4 2.4 0 0 1 2.4-2.4h4.8a2.4 2.4 0 0 1 2.4 2.4");
}

.ft5dv1b6b {
  fill: none;
}

.ih1wjzr2h {
  stop-color: var(--svg-color--074c7d, #074c7d);
}

.jmnik472b {
  d: path("M19.2 11.611c.372.42.6.984.6 1.59v1.2a2.4 2.4 0 0 1-2.4 2.4h-4.8a2.4 2.4 0 0 1-2.4-2.4v-.24l-1.2-.96v1.2a3.6 3.6 0 0 0 3.6 3.6h4.8a3.6 3.6 0 0 0 3.6-3.6v-1.2a3.6 3.6 0 0 0-1.8-3.12z");
}

.lq9lvnbri {
  stop-color: var(--svg-color--5d0b5d, #5d0b5d);
}

.y89swwoop {
  d: path("M9 10.2h1.2a2.4 2.4 0 0 1 2.4 2.4v.6h1.2v-.6A3.6 3.6 0 0 0 10.2 9H9a3.6 3.6 0 0 0-3.6 3.6v4.8A3.6 3.6 0 0 0 9 21h1.2a3.6 3.6 0 0 0 3.395-2.4h-1.32a2.4 2.4 0 0 1-2.076 1.2H9a2.4 2.4 0 0 1-2.4-2.4v-4.8A2.4 2.4 0 0 1 9 10.2");
}

</style>
