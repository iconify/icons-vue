<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="yhyrnlbfx"/><path fill="url(#SVG1DUySdsN)" class="tpwch9bez"/><path class="snkij6bur"/><path class="oytv22pdf"/><path class="h3b1jzbwv"/><path class="i9v4s0b6s"/><path class="k84_-ob6r"/><path class="z3g6dfbfe"/><path class="zojdilsom"/><path class="w7o9zobko"/><path class="u6c8zdbtb"/><defs><linearGradient id="SVG1DUySdsN" x1="12.002" x2="12.002" y1="2.996" y2="20.999" gradientUnits="userSpaceOnUse"><stop class="nuvpudbbg"/><stop offset="1" class="jvy3twb_v"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:sauce" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.h3b1jzbwv {
  fill: var(--svg-color--239454, #239454);
  d: path("M13.06 16.764c0-.265.301-1.175 1.058-.794c.53.264 0 1.059-1.059.794m-2.118 0c0-.265-.302-1.175-1.059-.794c-.53.264 0 1.059 1.059.794");
}

.i9v4s0b6s {
  fill: var(--svg-color--000, #000);
  d: path("M12.265 15.97h-.53v.53h.53z");
}

.jvy3twb_v {
  stop-color: var(--svg-color--1f201f, #1f201f);
}

.k84_-ob6r {
  fill: var(--svg-color--003d09, #003d09);
  d: path("M12.9 17.368c-.477.715-1.498.614-1.81-.016l.232-.116c.217.428.99.54 1.36-.016l.223.148z");
}

.nuvpudbbg {
  stop-color: var(--svg-color--30a45b, #30a45b);
}

.oytv22pdf {
  fill: var(--svg-color--2c9b61, #2c9b61);
  d: path("M9.903 12.122a3.6 3.6 0 0 0-1.058.01l-.043-.264a3.8 3.8 0 0 1 1.138-.006c.424.064.869.228 1.112.593l-.222.149c-.18-.27-.53-.419-.927-.477zm4.326.047a3.6 3.6 0 0 1 1.059.006l.042-.26a3.8 3.8 0 0 0-1.138-.005c-.424.063-.869.228-1.112.593l.222.148c.18-.27.53-.418.927-.476z");
}

.snkij6bur {
  fill: var(--svg-color--6bff53, #6bff53);
  d: path("M7.765 10.941C7.976 8.611 10.327 7.5 12 7.5s3.97 1.588 4.235 3.441c.037.265 0 .37 0 .53h-.53c-.09.264-.21.847 0 1.058c.266.265.53.53.53 1.06c0 .529-2.382 5.293-4.235 5.293s-4.235-4.764-4.235-5.294s.264-.794.53-1.059c.21-.211.09-.794 0-1.058h-.53z");
}

.tpwch9bez {
  d: path("M9.088 8.029c.423-.636 2.118-.97 2.912-1.06a5.2 5.2 0 0 1 2.911 1.06c.44-.265 1.112-.848 1.324-1.06c.265-.264 0-.264.265-.529c.264-.264.794.265.529.53c-.212.211-.355.354-.53.264c-.264.265-.793.953-.793 1.589c0 .635 1.058 1.588 1.058 2.117v2.118c.09 0 .265.106.265.53c0 .529-2.118 5.823-5.03 5.823c-2.911 0-5.029-5.559-5.029-5.824c0-.211.175-.439.265-.53V10.94c0-1.058 1.059-2.382 1.059-2.647c0-.212-.704-.794-1.059-1.059c-.175 0-.53-.053-.53-.264c0-.265.265-.53.53-.53c.212 0 .265.355.265.53z");
}

.u6c8zdbtb {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.677 13.853c0 .211-.175.44-.265.529c-1.06 0-1.853-1.323-1.06-1.323c.795 0 1.325.529 1.325.794m-1.589.794h.794v.264h-.794z");
}

.w7o9zobko {
  fill: var(--svg-color--000, #000);
  d: path("M11.47 14.647v1.059h-.793c-1.059 0-2.383-1.324-2.383-2.118c0-.635.705-.794 1.06-.794c1.058 0 2.117 1.059 2.117 1.853");
}

.yhyrnlbfx {
  fill: var(--svg-color--6bff53, #6bff53);
  fill-rule: evenodd;
  d: path("M12 20.47a8.47 8.47 0 1 0 0-16.94a8.47 8.47 0 0 0 0 16.94m0 .53a9 9 0 1 0 0-18a9 9 0 0 0 0 18");
}

.z3g6dfbfe {
  fill: var(--svg-color--000, #000);
  d: path("M12.53 14.647v1.059h.793c1.06 0 2.383-1.324 2.383-2.118c0-.635-.704-.794-1.06-.794c-1.058 0-2.117 1.059-2.117 1.853");
}

.zojdilsom {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.324 13.853c0 .211.174.44.264.529c1.06 0 1.853-1.323 1.06-1.323c-.795 0-1.324.529-1.324.794m1.588.794h-.794v.264h.794z");
}

</style>
