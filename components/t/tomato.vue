<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="js6o32bsh"/><path class="vfvftlb8e"/><g class="p--jj-p8v"><path class="mee2-kb3g"/><path class="bhaw94a8e"/><path class="c_mm0ubrw"/></g><ellipse class="sxds5p8ju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:tomato" /></template>
<style>
.bhaw94a8e {
  d: path("M13.9 14s9.2-6.9 17.3 0c-2.4-8.4-14.7-4.5-17.3 0m19.3.9c12.2 5.6 8.1 12 13.1 21c-3.4-7.5 5-21-13.1-21");
}

.c_mm0ubrw {
  d: path("M28.4 14s2.8-4.2 3.8-9.4c.1-.7 3.1-.6 3 .1c-1 6.7 1.7 10.4 1.7 10.4s-2.1.7-4.7.7c-2.6.1-3.8-1.8-3.8-1.8");
}

.js6o32bsh {
  fill: var(--svg-color--ef4d3c, #ef4d3c);
  d: path("M62 31.6C62.8 47 48.9 60 32.1 60S.4 46.2 2.1 30.9C4.5 9.4 20.4 8 32.1 8C39.2 8 60.2 1.8 62 31.6");
}

.mee2-kb3g {
  d: path("M11 27s7.3-13.5 19.9-12.3C19.8 9.6 11 20.4 11 27");
}

.p--jj-p8v {
  fill: var(--svg-color--64892f, #64892f);
}

.sxds5p8ju {
  cx: 33.7px;
  cy: 4.6px;
  fill: var(--svg-color--8cc63e, #8cc63e);
  rx: 1.5px;
  ry: 0.6px;
}

.vfvftlb8e {
  fill: var(--svg-color--8cc63e, #8cc63e);
  d: path("M11 27c6.2-9.6 16.8-6.8 19.6-10.4c0 6.9 5 3.5 7.5 6.6c3.2 4 4.4 11.1 8.2 12.5c-3.7-7.9 2.3-7.6-6.1-18.2c4.5 2.8 6.8 0 12.9 2.5c-5.3-8.4-13.6-6-13.6-6s5.2-4.8 9.6-2.3c-4.6-6.8-17.9 1.8-17.9 1.8s-5.5-9.4-17.3.5c6.9-2.8 14.5 0 14.5 0S15.9 10.9 11 27");
}

</style>
