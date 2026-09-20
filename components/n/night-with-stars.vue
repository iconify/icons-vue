<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="r7ynogw8h"/><path class="ftp1wqb4h"/><path class="ot-hu5bqv"/><path class="tdlp7ewuc"/><g class="n1mjunbsu"><circle class="ixkrodbdw"/><circle class="t9u3zqb4r"/><circle class="t1sxlacfb"/><circle class="ikodxzbol"/><circle class="w0adc89nc"/><circle class="iwseaq7ka"/><path class="eahwwvfbm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:night-with-stars" /></template>
<style>
.eahwwvfbm {
  d: path("M6.5 7A2.5 2.5 0 0 1 4 4.5c0-1.13.755-2.074 1.784-2.383A3 3 0 0 0 5 2a3 3 0 1 0 0 6c.959 0 1.803-.458 2.353-1.159A2.5 2.5 0 0 1 6.5 7");
}

.ftp1wqb4h {
  fill: var(--svg-color--3f484c, #3f484c);
  d: path("M10 36V7l4-4h2l4 4v29zm23-25c0-1-1-1-1-1h-7s-1 0-1 1v25h9z");
}

.ikodxzbol {
  cx: 26.5px;
  cy: 5.5px;
  r: 0.5px;
}

.iwseaq7ka {
  cx: 31.5px;
  cy: 7.5px;
  r: 0.5px;
}

.ixkrodbdw {
  cx: 10.5px;
  cy: 2.5px;
  r: 0.5px;
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.ot-hu5bqv {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M28 19c0-1-1-1-1-1h-8c-1 0-1 1-1 1v17h10zm-17 2H6v-7s0-1-1-1H0v19a4 4 0 0 0 4 4h8V22s0-1-1-1m21 4c-1 0-1 1-1 1v10h1a4 4 0 0 0 4-4v-7z");
}

.r7ynogw8h {
  fill: var(--svg-color--269, #269);
  d: path("M32 0H4a4 4 0 0 0-4 4v22h36V4a4 4 0 0 0-4-4");
}

.t1sxlacfb {
  cx: 22px;
  cy: 5px;
  r: 1px;
}

.t9u3zqb4r {
  cx: 7.5px;
  cy: 11.5px;
  r: 0.5px;
}

.tdlp7ewuc {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
  d: path("M8 31h2v2H8zm0-8h2v2H8zm-2 4h2v2H6zM16 9h2v2h-2zm0 4h2v2h-2zm-2 4h2v2h-2zm10 3h2v2h-2zm-2 4h2v2h-2zm-2 6h2v2h-2zm9-18h2v2h-2zm0 4h2v2h-2z");
}

.w0adc89nc {
  cx: 31px;
  cy: 3px;
  r: 1px;
}

</style>
