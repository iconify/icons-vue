<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":159};
const content = `<defs><linearGradient id="SVGnjwo7bTh" x1="50%" x2="0%" y1="33.756%" y2="100%"><stop offset="0%" class="zywy4f5gt"/><stop offset="100%" class="vpz5z8h2c"/></linearGradient></defs><g class="ft5dv1b6b"><path class="mpn0pmb_x"/><path class="xiydfsmfm"/><path fill="url(#SVGnjwo7bTh)" class="whny9ib0i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:maildeveloper" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mpn0pmb_x {
  fill: var(--svg-color--393e42, #393e42);
  d: path("M21.331 158.118v-42.165h128v42.165z");
}

.vpz5z8h2c {
  stop-color: var(--svg-color--303439, #303439);
}

.whny9ib0i {
  d: path("M252.755 54.37c2.07 7.228 3.245 15.413 3.245 24.689c0 79.059-85.33 79.059-85.33 79.059V21.082s51.365 8.787 82.085 33.288m-82.086-12.205v73.788s41.788 0 42.662-36.894c.88-36.894-42.662-36.894-42.662-36.894");
}

.xiydfsmfm {
  fill: var(--svg-color--60676f, #60676f);
  d: path("M0 158.118V0h42.67l42.66 42.165L128 0h42.67S256 0 256 79.059s-85.33 79.059-85.33 79.059H128V52.706L85.33 94.87L42.67 52.706v105.412zM170.67 42.165v73.788s41.787 0 42.66-36.894c.882-36.894-42.66-36.894-42.66-36.894");
}

.zywy4f5gt {
  stop-color: var(--svg-color--60676f, #60676f);
}

</style>
