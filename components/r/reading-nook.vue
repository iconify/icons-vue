<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wp80m_bnb"/><path class="em1em93gc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:reading-nook" /></template>
<style>
.em1em93gc {
  d: path("M5 12.25V10.5A1.5 1.5 0 0 1 6.5 9H11a1.5 1.5 0 0 1 1.5 1.5v1.75m6 8.75V8m-3 0l1.25-4.5h3.5L21.5 8Zm.5 13h5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wp80m_bnb {
  d: path("M3 14a1.75 1.75 0 0 1 3.5 0v1.5H11V14a1.75 1.75 0 0 1 3.5 0v5H3Z");
}

</style>
