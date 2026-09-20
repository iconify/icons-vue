<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="dt460vb3h"/><path class="jyigohi0x"/><path class="b2s95kade"/><path class="crxfnztgq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:sbtc" /></template>
<style>
.b2s95kade {
  fill: var(--svg-color--4e4294, #4e4294);
  d: path("M12 21a9 9 0 0 0 7.796-13.5h-4.42a5.61 5.61 0 0 1 2.249 4.499a5.624 5.624 0 0 1-5.616 5.624l.004.002h-7.04A8.98 8.98 0 0 0 12 21m-7.796-4.5A8.96 8.96 0 0 1 3 12a9 9 0 0 1 16.026-5.625H12A5.624 5.624 0 0 0 8.627 16.5z");
}

.crxfnztgq {
  fill: var(--svg-color--f08619, #f08619);
  d: path("M12.972 10.875h-2.097v.562h2.097c.05-.016.153-.093.153-.271s-.102-.269-.153-.291m0 1.688h-2.097v.562h2.097c.05-.016.153-.093.153-.272c0-.178-.102-.268-.153-.29");
}

.dt460vb3h {
  fill: var(--svg-color--f08619, #f08619);
  d: path("M12 16.5a4.5 4.5 0 1 0 0-9a4.5 4.5 0 0 0 0 9");
}

.ft5dv1b6b {
  fill: none;
}

.jyigohi0x {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.75 14.25v-4.5h3.26c.793 0 1.24.748 1.24 1.346c0 .479-.207.782-.31.873c.248.25.31.702.31.897c.02.858-.707 1.384-1.104 1.384z");
}

</style>
