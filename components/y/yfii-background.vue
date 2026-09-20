<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="cxsmfv2jb"/><path class="iquyexb_e"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:yfii-background" /></template>
<style>
.cxsmfv2jb {
  fill: var(--svg-color--ff267e, #ff267e);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.iquyexb_e {
  fill: var(--svg-color--fff, #fff);
  d: path("m10.38 6.907l.903 3.402l-3.53.759l-.23-1.012l1.894-.417s-1.63-1.116-3.31.287c-.692.579-.937 1.49-.937 1.907c0 .607.168 2.275 2.067 2.868c1.383.257 2.692-.318 3.3-1.9h1.172s-.57 1.86-1.95 2.565c-.787.402-2.306.894-3.964-.089C4.722 14.515 4 13.59 4 11.797c0-1.365 1.436-3.948 4.277-3.6c.63.076 1.299.357 1.299.357L9.279 7.21zm6.82 5.495H6.798v-.8H17.2zm-4.483 1.289l.902 3.402l1.101-.304l-.296-1.343s.668.28 1.299.358c2.84.347 4.277-2.236 4.277-3.601c0-1.791-.723-2.718-1.795-3.48c-1.659-.983-3.177-.49-3.964-.09c-1.38.705-1.95 2.568-1.95 2.568h1.172c.608-1.581 1.917-2.16 3.3-1.901c1.9.592 2.068 2.26 2.068 2.867c0 .417-.245 1.328-.938 1.907c-1.679 1.403-3.31.287-3.31.287l1.894-.417l-.23-1.012z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
