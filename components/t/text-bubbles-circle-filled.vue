<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGAFQ9lEPv"><path class="k5-vjlrin"/><g class="ivjvz2eii"><path class="enqy9euwg"/><path class="quqx3pb7p"/><path class="t67ooylad"/></g></mask></defs><circle mask="url(#SVGAFQ9lEPv)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:text-bubbles-circle-filled" /></template>
<style>
.bd9gczbnq {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

.enqy9euwg {
  d: path("M8.53 11.38c.46 0 .83-.37.83-.83s-.37-.83-.83-.83s-.83.37-.83.83s.37.83.83.83m2.5 0c.46 0 .83-.37.83-.83s-.37-.83-.83-.83s-.83.37-.83.83s.37.83.83.83m2.5 0c.46 0 .83-.37.83-.83s-.37-.83-.83-.83s-.83.37-.83.83s.37.83.83.83");
}

.ft5dv1b6b {
  fill: none;
}

.ivjvz2eii {
  fill: var(--svg-color--000, #000);
}

.k5-vjlrin {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

.quqx3pb7p {
  d: path("M8.28 16.97c-.86 0-1.36-.75-1.65-1.59a2.66 2.66 0 0 1-2.44-2.66V8.46C4.19 7 5.39 5.8 6.86 5.8h8.33c1.47 0 2.67 1.2 2.67 2.67v4.25c0 1.47-1.2 2.67-2.67 2.67h-4.24c-1.8 1.58-2.43 1.58-2.67 1.58M6.86 7.8c-.36 0-.67.31-.67.67v4.25c0 .36.3.66.66.66H8.2l.17.79c.04.18.1.39.16.57c.37-.26.9-.68 1.36-1.1l.29-.26h5.01c.36 0 .67-.31.67-.67V8.47c0-.36-.3-.67-.67-.67z");
}

.t67ooylad {
  d: path("M18.22 20.3c-.23 0-.76 0-2.21-1.27h-2.48c-1.29 0-2.33-1.05-2.33-2.33c0-.55.45-1 1-1s1 .45 1 1c0 .18.15.33.33.33h3.25l.29.26c.28.25.59.51.85.7c.02-.06.03-.12.04-.17l.17-.79h1.24c.18 0 .33-.15.33-.34v-3.4c0-.18-.15-.33-.33-.33c-.55 0-1-.45-1-1s.45-1 1-1c1.29 0 2.33 1.05 2.33 2.33v3.4c0 1.18-.88 2.15-2.01 2.31c-.25.65-.69 1.29-1.46 1.29z");
}

</style>
