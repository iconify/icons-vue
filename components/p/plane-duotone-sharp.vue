<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="tw57akb8a"/><path class="rtns-0bgw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:plane-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.rtns-0bgw {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m19 8l-3 3l2 8l-2 2l-4-6l-3 2v3l-1 1l-2-3l-3-2l1-1h3l2-3l-6-4l2-2l8 2l3-3c2-2 3-2 4-1s1 2-1 4");
}

.tw57akb8a {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m17.107 11.307l1.863 7.45c.085.341-.015.702-.263.95l-2 2a.998.998 0 0 1-1.539-.152l-3.445-5.168L10 17.535V20c0 .265-.105.52-.293.707l-1 1a.998.998 0 0 1-1.539-.152l-1.889-2.834l-2.834-1.889a.998.998 0 0 1-.152-1.539l1-1A1 1 0 0 1 4 14h2.465l1.148-1.723l-5.168-3.445a.998.998 0 0 1-.152-1.539l2-2c.248-.248.609-.348.95-.263l7.45 1.863l2.6-2.6c.77-.771 1.784-1.678 2.886-1.899c.99-.197 1.836.207 2.528.899c1.951 1.952.536 3.878-1 5.414Z");
}

</style>
