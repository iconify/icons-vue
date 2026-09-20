<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<defs><linearGradient id="SVGIhZDlJ6y" x1="75.7%" x2="-19.467%" y1="132.917%" y2="11.033%"><stop offset="6%" class="r_lf9ybqi"/><stop offset="87%" class="z65hc5b4d"/></linearGradient><linearGradient id="SVGCNjPIeGm" x1="76.465%" x2="28.668%" y1="92.417%" y2="-29.467%"><stop offset="5%" class="r_lf9ybqi"/><stop offset="18%" class="lh_uwtodl"/><stop offset="39%" class="i1bqhjbcd"/><stop offset="67%" class="sppw-bcqt"/><stop offset="87%" class="z65hc5b4d"/></linearGradient><linearGradient id="SVGZpAPVdcI" x1="33.801%" x2="64.854%" y1="103.028%" y2="-21.398%"><stop offset="12%" class="z65hc5b4d"/><stop offset="36%" class="x8uo-2btw"/><stop offset="58%" class="gekh5u30x"/><stop offset="77%" class="yb5kgfbuu"/><stop offset="92%" class="cnhu0fbnw"/><stop offset="100%" class="bzg--8baj"/></linearGradient></defs><path fill="url(#SVGIhZDlJ6y)" class="f-bkgmp3y"/><path fill="url(#SVGCNjPIeGm)" class="dpmbaju7x"/><path fill="url(#SVGZpAPVdcI)" class="k7hlwrpvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:mps-icon" /></template>
<style>
.bzg--8baj {
  stop-color: var(--svg-color--fcf84a, #fcf84a);
}

.cnhu0fbnw {
  stop-color: var(--svg-color--f2f64d, #f2f64d);
}

.dpmbaju7x {
  d: path("M256 256L127.403 127.659L256 0z");
}

.f-bkgmp3y {
  d: path("M0 256h256L127.403 127.659L0 0z");
}

.gekh5u30x {
  stop-color: var(--svg-color--a9eb62, #a9eb62);
}

.i1bqhjbcd {
  stop-color: var(--svg-color--1099d6, #1099d6);
}

.k7hlwrpvz {
  d: path("m191.573 191.616l-64.17-63.957L256 0z");
}

.lh_uwtodl {
  stop-color: var(--svg-color--0a84f0, #0a84f0);
}

.r_lf9ybqi {
  stop-color: var(--svg-color--087cfa, #087cfa);
}

.sppw-bcqt {
  stop-color: var(--svg-color--19baad, #19baad);
}

.x8uo-2btw {
  stop-color: var(--svg-color--6ae274, #6ae274);
}

.yb5kgfbuu {
  stop-color: var(--svg-color--d6f255, #d6f255);
}

.z65hc5b4d {
  stop-color: var(--svg-color--21d789, #21d789);
}

</style>
