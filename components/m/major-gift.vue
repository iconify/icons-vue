<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o5cfenprm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:major-gift" /></template>
<style>
.o5cfenprm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.4 12H3.5V8h17v4H20m-3 0h-1.3M5 12v7.5q0 .074.007.147t.022.146q.014.072.036.142q.021.071.049.139t.063.133t.076.126q.041.062.087.119q.047.057.099.109t.109.099t.119.087t.126.076t.133.063t.139.049t.142.036q.073.015.146.022T6.5 21h5.979M12 8c-1-3.5-5-5.5-5-2.5C7 7 9 8 12 8s5-1 5-2.5c0-3-4-1-5 2.5m0 4v9m3.25-.25v-5l1.75 2L18.5 15l1.5 2.75l1.75-2v5Z");
}

</style>
