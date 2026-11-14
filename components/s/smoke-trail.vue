<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="beejo3pgp"/><path class="hjkz6acjs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:smoke-trail" /></template>
<style>
.beejo3pgp {
  d: path("m20.182 3.818l-.354 1.768l-1.237 1.237l1.061 3.889l-.707.707l-1.768-3.182l-1.591 1.591l.177 1.591l-.531.531l-1.237-1.945l-1.945-1.237l.531-.531l1.591.177l1.591-1.591l-3.182-1.768l.707-.707l3.889 1.061l1.237-1.237Z");
}

.hjkz6acjs {
  d: path("M14 10c-6 6.5-11 4-9.5 1s6-1 4 3.5c-1.25 2.75-3.5 5-6 6.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
