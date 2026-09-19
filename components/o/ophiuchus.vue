<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="iqhz24bmv"/><g class="n1mjunbsu"><path class="fpt3nzbsg"/><path class="tg1n0h55f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:ophiuchus" /></template>
<style>
.fpt3nzbsg {
  d: path("M32 54c-9.4 0-17-7.6-17-17V14h6v23c0 6.1 4.9 11 11 11s11-4.9 11-11V14h6v23c0 9.4-7.6 17-17 17");
}

.iqhz24bmv {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--c28fef, #c28fef);
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.tg1n0h55f {
  d: path("M56 22c-2.6 4.1-6.1 6-8.4 7.2c-3.5 2-7.9-.2-11.7-2.1q-1.8-.9-3.3-1.5c-10.9-4.2-19.1-.5-24.6 4.9V38c3.6-4.8 12.1-10.3 22.5-6.2c.8.3 1.8.8 2.8 1.3c4 2 9.2 4.6 14.5 3c.8-.2 1.7-.6 2.5-1.1c2-1.2 4-2.1 5.6-4.5z");
}

</style>
