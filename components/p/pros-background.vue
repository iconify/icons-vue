<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path class="tbczr9uvi"/><path class="onx716i1f"/><path fill="url(#SVG9co0ebok)" clip-rule="evenodd" class="mrcn2fble"/><path fill="url(#SVGE1jj6dDX)" clip-rule="evenodd" class="fp0e3x1at"/></g><defs><linearGradient id="SVG9co0ebok" x1="16.329" x2="10.341" y1="10.039" y2="15.994" gradientUnits="userSpaceOnUse"><stop class="lv5oa4vqb"/><stop offset=".817" class="xs076xski"/></linearGradient><linearGradient id="SVGE1jj6dDX" x1="9.759" x2="14.391" y1="14.748" y2="10.909" gradientUnits="userSpaceOnUse"><stop class="yek7wiboa"/><stop offset="1" class="faq-wij2e"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:pros-background" /></template>
<style>
.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.faq-wij2e {
  stop-color: var(--svg-color--01fdfe, #01fdfe);
  stop-opacity: 0.06;
}

.fp0e3x1at {
  fill-rule: evenodd;
  d: path("m14.79 9.186l.036.036c2.49 2.49 3.254 5.763 1.707 7.31c-1.548 1.548-4.82.784-7.31-1.706l-.022-.022l.9-.905l.024.025c1.981 1.982 4.438 2.737 5.487 1.688s.294-3.507-1.687-5.488l-.035-.034z");
}

.ft5dv1b6b {
  fill: none;
}

.lv5oa4vqb {
  stop-color: var(--svg-color--fbfcfa, #fbfcfa);
}

.mrcn2fble {
  fill-rule: evenodd;
  d: path("m9.21 14.814l-.037-.036c-2.49-2.49-3.253-5.764-1.706-7.31c1.547-1.549 4.82-.785 7.31 1.705l.021.023l-.9.904l-.024-.024c-1.98-1.982-4.437-2.738-5.486-1.688c-1.05 1.05-.294 3.507 1.687 5.488l.034.034z");
}

.onx716i1f {
  fill: var(--svg-color--333, #333);
  d: path("M11.921 11.921L20 4v16H4z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.tbczr9uvi {
  fill: var(--svg-color--5901f6, #5901f6);
  d: path("M24 0L0 24V0z");
}

.xs076xski {
  stop-color: var(--svg-color--9359fd, #9359fd);
  stop-opacity: 0.07;
}

.yek7wiboa {
  stop-color: var(--svg-color--01fdfe, #01fdfe);
}

</style>
