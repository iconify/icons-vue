<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="b3ayrcc1x"/><path class="lp5zyobgd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:recycle-bulk-sharp" /></template>
<style>
.b3ayrcc1x {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3.34 19a1 1 0 0 1-.866-1.5l3.853-6.674l-1.766.473a1 1 0 1 1-.518-1.931L8.14 8.27l.001-.001a1 1 0 0 1 1.225.708l1.098 4.098a1 1 0 0 1-.705 1.224a1 1 0 0 1-1.227-.707l-.473-1.766L5.072 17H6.34a1 1 0 0 1 0 2Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.lp5zyobgd {
  d: path("M11.134 2.5a1.002 1.002 0 0 1 1.732 0l3.853 6.674l.473-1.766a1 1 0 0 1 1.932.517l-1.098 4.098a.997.997 0 0 1-1.225.708l-4.098-1.099a1 1 0 1 1 .518-1.931l1.766.473L12 5l-.634 1.098a1 1 0 0 1-1.732-1Zm1.82 14.5h5.974l-.634-1.098a1 1 0 0 1 1.732-1l1.5 2.598a.998.998 0 0 1-.866 1.5h-7.706l1.293 1.293a1 1 0 0 1-1.414 1.414l-3-3a1 1 0 0 1 0-1.414l3-3a.999.999 0 1 1 1.414 1.414Z");
}

</style>
