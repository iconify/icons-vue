<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="x00w542jp"/><path class="vhzplcb3s"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:stat-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.vhzplcb3s {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.486 9.29a.747.747 0 1 0-.63-1.355l-5.1-2.942a.745.745 0 1 0-1.49 0L7.12 7.9a.745.745 0 0 0-.701 1.307v5.865l-.988-.556l.19-.359H4l.88 1.399l.194-.378l7.951 4.574l5.754-3.34c.126.097.28.16.45.16a.745.745 0 0 0 .262-1.452V9.295zM7.14 15.504V9.266l.087-.049l5.483 3.18v6.276zm5.855-3.775L7.571 8.555V8.5l5.053-2.85a.74.74 0 0 0 .779 0l5.033 2.874L13 11.734zm.74.436l5.024-2.991v5.962zm-.3.667l5 2.952l-5 2.89z");
}

.x00w542jp {
  fill: var(--svg-color--21353e, #21353e);
  d: path("M24 0H0v24h24z");
}

</style>
