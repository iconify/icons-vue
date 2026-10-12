<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wp4zwl7gy"/><path class="duhk3xbzk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:remodel-house" /></template>
<style>
.duhk3xbzk {
  d: path("m11.34 15.09l3.75-3.75q.42-.42.85 0l.91.92q.43.42.01.84l-3.76 3.76q-.42.42-.84-.01l-.92-.91q-.42-.43 0-.85m3.64-.11l4.95 4.95");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wp4zwl7gy {
  d: path("M2.75 18.75v-9.8q0-1 .78-1.62l4.94-3.96q.78-.62 1.56 0l4.94 3.96q.78.62.78 1.62v9.8q0 1-1 1h-11q-1 0-1-1");
}

</style>
