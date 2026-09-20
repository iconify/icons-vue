<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGN3g0DgEk)" class="r4i437pya"/><path class="e74fcibhf"/><path class="jgfjjibcb"/><path class="t51en4adx"/></g><defs><linearGradient id="SVGN3g0DgEk" x1="6.064" x2="16.496" y1="12.119" y2="9.656" gradientUnits="userSpaceOnUse"><stop class="hfsaa6byy"/><stop offset=".52" class="w_xr1w2wj"/><stop offset=".72" class="q9d4ote5d"/><stop offset=".85" class="jgkc-abgs"/><stop offset="1" class="s5tlhuumk"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:rgen-background" /></template>
<style>
.e74fcibhf {
  fill: var(--svg-color--fff, #fff);
  d: path("m6.17 9.245l5.022-4.973l1.026.871l-5.092 5.035l4.897 4.844l4.897-4.844l-.831-.822l-.955.947l-.89-.983l.907-.897a1.395 1.395 0 0 1 1.93.03l.715.712a1.43 1.43 0 0 1 .314 1.562c-.073.174-.18.332-.314.464l-4.747 4.693a1.46 1.46 0 0 1-2.053 0L6.17 11.111a1.31 1.31 0 0 1 0-1.866");
}

.ft5dv1b6b {
  fill: none;
}

.hfsaa6byy {
  stop-color: var(--svg-color--873b9f, #873b9f);
}

.jgfjjibcb {
  fill: var(--svg-color--fff, #fff);
  d: path("m14.324 9.231l.431-.426a1.78 1.78 0 0 0 .462 1.51l2.529 2.503l-.476 1.35l-2.946-2.91a1.42 1.42 0 0 1 0-2.027");
}

.jgkc-abgs {
  stop-color: var(--svg-color--327ec2, #327ec2);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q9d4ote5d {
  stop-color: var(--svg-color--2867ac, #2867ac);
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.s5tlhuumk {
  stop-color: var(--svg-color--27abe3, #27abe3);
}

.t51en4adx {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.85 5.13c-.374-.347-1.085-.209-1.414-.107l.551-.604a1.46 1.46 0 0 1 2.049 0l.76.755a1.423 1.423 0 0 1 0 2.022L7.067 13.85l4.96 4.906c1.43-1.408 4.408-4.346 4.862-4.804c.453-.462.31-1.4.177-1.809l.711.698a1.42 1.42 0 0 1 0 2.027l-4.804 4.746a1.35 1.35 0 0 1-1.893 0l-4.804-4.75a1.42 1.42 0 0 1 0-2.027l6.729-6.653z");
}

.w_xr1w2wj {
  stop-color: var(--svg-color--359dda, #359dda);
}

</style>
