<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGbKCEFdNo)" class="r4i437pya"/><path class="rv8fatbkn"/></g><defs><linearGradient id="SVGbKCEFdNo" x1="8.714" x2="15.012" y1="5.304" y2="19.15" gradientUnits="userSpaceOnUse"><stop class="xabpkybjo"/><stop offset=".38" class="z4r7ovg-y"/><stop offset=".73" class="l73tyqb3g"/><stop offset="1" class="l01fejbda"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:rev3l-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.l01fejbda {
  stop-color: var(--svg-color--c56058, #c56058);
}

.l73tyqb3g {
  stop-color: var(--svg-color--622065, #622065);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.rv8fatbkn {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.5 4.5L14 7H8.665C7.89 7 6.5 7.59 6.5 9.5s1.47 2.385 2.25 2.5h2.5L7.5 19.5H4.25L7 14c-1-.34-3-1.225-3-4.5s3-5 4.5-5zm-7 15L9.75 17h5.585c.775 0 2.165-.59 2.165-2.5s-1.47-2.385-2.25-2.5H12.5l4-7.5h3.25L17 9.95c1 .35 3 1.275 3 4.55s-2.5 5-4.5 5z");
}

.xabpkybjo {
  stop-color: var(--svg-color--242a3f, #242a3f);
}

.z4r7ovg-y {
  stop-color: var(--svg-color--321b65, #321b65);
}

</style>
