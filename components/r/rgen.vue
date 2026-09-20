<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGfTTnEcoe)" class="h9hnqgh4j"/><path fill="url(#SVGn9fiKcGy)" class="eyfky6bck"/><path fill="url(#SVGaHcxGceJ)" class="dmx54dnsh"/><defs><linearGradient id="SVGfTTnEcoe" x1="5.322" x2="17.058" y1="12.134" y2="9.364" gradientUnits="userSpaceOnUse"><stop class="hfsaa6byy"/><stop offset=".52" class="w_xr1w2wj"/><stop offset=".72" class="q9d4ote5d"/><stop offset=".85" class="jgkc-abgs"/><stop offset="1" class="s5tlhuumk"/></linearGradient><linearGradient id="SVGn9fiKcGy" x1="5.575" x2="17.837" y1="8.1" y2="20.634" gradientUnits="userSpaceOnUse"><stop offset=".31" class="g70tt6bmf"/><stop offset="1" class="axm58rbbb"/></linearGradient><linearGradient id="SVGaHcxGceJ" x1="5.081" x2="12.935" y1="14.62" y2="14.925" gradientUnits="userSpaceOnUse"><stop class="exdseubrn"/><stop offset="1" class="lf5efybsu"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:rgen" /></template>
<style>
.axm58rbbb {
  stop-color: var(--svg-color--286db0, #286db0);
}

.dmx54dnsh {
  d: path("M11.83 4.271c-.42-.39-1.22-.235-1.59-.12l.62-.68a1.645 1.645 0 0 1 2.305 0l.855.85a1.6 1.6 0 0 1 0 2.275L6.45 14.08l5.58 5.52c1.61-1.585 4.96-4.89 5.47-5.405c.51-.52.35-1.575.2-2.035l.8.785a1.6 1.6 0 0 1 .353 1.758a1.6 1.6 0 0 1-.353.522l-5.405 5.34a1.52 1.52 0 0 1-2.13 0L5.561 15.22a1.6 1.6 0 0 1 0-2.28l7.57-7.484z");
}

.exdseubrn {
  stop-color: var(--svg-color--813b9d, #813b9d);
}

.eyfky6bck {
  d: path("m14.614 8.885l.485-.48a2 2 0 0 0 .52 1.7l2.845 2.815l-.535 1.52l-3.315-3.275a1.6 1.6 0 0 1 0-2.28");
}

.ft5dv1b6b {
  fill: none;
}

.g70tt6bmf {
  stop-color: var(--svg-color--2caae2, #2caae2);
}

.h9hnqgh4j {
  d: path("m5.441 8.9l5.65-5.594l1.155.98l-5.73 5.665l5.51 5.449l5.51-5.45l-.936-.924l-1.075 1.065l-1-1.105l1.02-1.01a1.57 1.57 0 0 1 2.17.035l.805.8a1.6 1.6 0 0 1 .353 1.757a1.6 1.6 0 0 1-.353.522l-5.34 5.28a1.645 1.645 0 0 1-2.31 0L5.442 11a1.477 1.477 0 0 1 0-2.1");
}

.hfsaa6byy {
  stop-color: var(--svg-color--873b9f, #873b9f);
}

.jgkc-abgs {
  stop-color: var(--svg-color--327ec2, #327ec2);
}

.lf5efybsu {
  stop-color: var(--svg-color--24ade3, #24ade3);
}

.q9d4ote5d {
  stop-color: var(--svg-color--2867ac, #2867ac);
}

.s5tlhuumk {
  stop-color: var(--svg-color--27abe3, #27abe3);
}

.w_xr1w2wj {
  stop-color: var(--svg-color--359dda, #359dda);
}

</style>
