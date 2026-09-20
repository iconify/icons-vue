<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="q2my2lb_y"/><path class="pl04sabxw"/><path class="lf1_s9bjf"/><path class="d4poxqbze"/><path class="zyet41big"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:zig" /></template>
<style>
.d4poxqbze {
  fill: var(--svg-color--6640c7, #6640c7);
  d: path("M7.064 4.028c0-.57.447-1.028.999-1.028h.905c.552 0 1 .465 1 1.028v8.396c0 .569-.448 1.027-1 1.027h-.905c-.552 0-.999-.464-.999-1.027z");
}

.ft5dv1b6b {
  fill: none;
}

.lf1_s9bjf {
  fill: var(--svg-color--936ed8, #936ed8);
  d: path("M14.032 11.552c0-.551.447-1.004.998-1.004h.906c.552 0 .999.453.999 1.004v6.12c0 .552-.447 1.005-.999 1.005h-.906c-.551 0-.998-.453-.998-1.005z");
}

.pl04sabxw {
  fill: var(--svg-color--ac8ce1, #ac8ce1);
  d: path("M17.516 9.179c0-.523.447-.952.999-.952h.906c.551 0 .998.43.998.952v3.902c0 .522-.447.952-.998.952h-.906c-.552 0-.999-.43-.999-.952z");
}

.q2my2lb_y {
  fill: var(--svg-color--734acc, #734acc);
  d: path("M3.58 9.307c0-.599.448-1.08 1-1.08h.905c.552 0 .999.481.999 1.08v4.807c0 .598-.447 1.08-.999 1.08h-.906c-.551 0-.998-.482-.998-1.08z");
}

.zyet41big {
  fill: var(--svg-color--8961d4, #8961d4);
  d: path("M10.549 5.764c0-.563.447-1.022.998-1.022h.906c.552 0 .999.459.999 1.022v14.214c0 .563-.447 1.022-.999 1.022h-.906c-.551 0-.998-.459-.998-1.022z");
}

</style>
