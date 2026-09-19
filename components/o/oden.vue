<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="dmqrqmbla"/><path class="q40_97bdd"/><path class="k1r1bq5ts"/><ellipse transform="rotate(-45.001 31.162 31.164)" class="zhhec6bed"/><path class="a8f1wtb8o"/><path class="c93s0bb7t"/><path class="z48pgpz3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:oden" /></template>
<style>
.a8f1wtb8o {
  fill: var(--svg-color--f29a2e, #f29a2e);
  d: path("M22 19.5c-.7-.7-1.8-.7-2.5 0s-.7 1.8 0 2.5l3.9 3.9c.7.7 1.8.7 2.5 0s.7-1.8 0-2.5z");
}

.c93s0bb7t {
  fill: var(--svg-color--62727a, #62727a);
  d: path("M29.9 7c4.9 4.9-1.2 10.5-6.8 16.1S12 34.9 7 29.9C4.4 27.3 1.9 8.6 5.2 5.2S27.3 4.4 29.9 7");
}

.dmqrqmbla {
  fill: var(--svg-color--f29a2e, #f29a2e);
  d: path("M52.3 49.8c-.7-.7-1.8-.7-2.5 0s-.7 1.8 0 2.5l7.3 7.3c.7.7 1.8.7 2.5 0s.7-1.8 0-2.5z");
}

.k1r1bq5ts {
  fill: var(--svg-color--f29a2e, #f29a2e);
  d: path("M39 36.5c-.7-.7-1.8-.7-2.5 0s-.7 1.8 0 2.5l3.9 3.9c.7.7 1.8.7 2.5 0s.7-1.8 0-2.5z");
}

.q40_97bdd {
  fill: var(--svg-color--dae3ea, #dae3ea);
  d: path("M60.7 38.6c1.6 1.6 1.7 4 .3 5.4L44 61c-1.4 1.4-3.8 1.3-5.4-.3L30.9 53c-1.6-1.6-1.7-4-.3-5.4l17-17c1.4-1.4 3.8-1.3 5.4.3z");
}

.z48pgpz3i {
  fill: var(--svg-color--f29a2e, #f29a2e);
  d: path("M5 2.5c-.7-.7-1.8-.7-2.5 0s-.7 1.8 0 2.5l3.9 3.9c.7.7 1.8.7 2.5 0s.7-1.8 0-2.5z");
}

.zhhec6bed {
  cx: 31.2px;
  cy: 31.2px;
  fill: var(--svg-color--8e725e, #8e725e);
  rx: 14.4px;
  ry: 12.6px;
}

</style>
