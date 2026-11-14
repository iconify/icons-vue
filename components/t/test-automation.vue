<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sbd-s5wnd"/><path class="t08wuz0fb"/><path class="k57ggj4vq"/><path class="niy0uvcpl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:test-automation" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k57ggj4vq {
  d: path("M19.794 7.5A9 9 0 1 1 7.5 4.206");
}

.niy0uvcpl {
  d: path("m5 3.5l2.5.75l-.75 2.5");
}

.sbd-s5wnd {
  d: path("m10.954 7.384l.001-.011a.864.864 0 0 1 .86-.786h.37a.864.864 0 0 1 .86.786l.001.011a1.5 1.5 0 0 0 .744 1.164l.305.176a1.5 1.5 0 0 0 1.38.062l.01-.005a.864.864 0 0 1 1.11.352l.185.321a.864.864 0 0 1-.25 1.137l-.009.007a1.5 1.5 0 0 0-.636 1.226v.352a1.5 1.5 0 0 0 .636 1.226l.009.007a.864.864 0 0 1 .25 1.137l-.185.321a.864.864 0 0 1-1.11.352l-.01-.005a1.5 1.5 0 0 0-1.38.062l-.305.176a1.5 1.5 0 0 0-.744 1.164l-.001.011a.864.864 0 0 1-.86.786h-.37a.864.864 0 0 1-.86-.786l-.001-.011a1.5 1.5 0 0 0-.744-1.164l-.305-.176a1.5 1.5 0 0 0-1.38-.062l-.01.005a.864.864 0 0 1-1.11-.352l-.185-.321a.864.864 0 0 1 .25-1.137l.009-.007a1.5 1.5 0 0 0 .636-1.226v-.352a1.5 1.5 0 0 0-.636-1.226l-.009-.007a.864.864 0 0 1-.25-1.137l.185-.321a.864.864 0 0 1 1.11-.352l.01.005a1.5 1.5 0 0 0 1.38-.062l.305-.176a1.5 1.5 0 0 0 .744-1.164");
}

.t08wuz0fb {
  d: path("M10.25 12a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

</style>
