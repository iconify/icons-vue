<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wuh51vj3z"/><path class="cqyetk7ve"/><path class="nr2kwkbiv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:rx-copay" /></template>
<style>
.cqyetk7ve {
  d: path("M7 12.5v-7h3a2.25 2.25 0 0 1 0 4.5H7m2 0l3.5 4m-3 0l3.5-3.5m1 7.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

.nr2kwkbiv {
  d: path("M17 15h2a3 3 0 0 1 0 6h-2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wuh51vj3z {
  d: path("M12.4 21.5H3v-19h14v9.7");
}

</style>
