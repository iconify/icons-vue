<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="b6c3fdnyi"/><path class="dxo1vobdi"/><path class="qe2o-__ci"/><path class="fslrlub5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:two-oclock" /></template>
<style>
.b6c3fdnyi {
  cx: 31.926px;
  cy: 31.924px;
  r: 29.574px;
  fill: var(--svg-color--e0e7ec, #e0e7ec);
}

.dxo1vobdi {
  fill: var(--svg-color--98a9b4, #98a9b4);
  d: path("M0 31.926C0 49.529 14.321 63.85 31.924 63.85S63.85 49.531 63.85 31.926S49.527 0 31.924 0S0 14.321 0 31.926m6.215 0c0-14.179 11.534-25.712 25.708-25.712c14.177 0 25.711 11.534 25.711 25.712c0 14.176-11.534 25.709-25.711 25.709c-14.174 0-25.708-11.533-25.708-25.709");
}

.fslrlub5g {
  fill: var(--svg-color--788288, #788288);
  d: path("M46.15 25.08c1.162-.84 1.606-2.206.998-3.05c-.61-.84-2.051-.842-3.211 0L31.61 30.961c-1.158.84-1.606 2.212-.994 3.05c.609.844 2.047.846 3.207.008z");
}

.qe2o-__ci {
  fill: var(--svg-color--85939c, #85939c);
  d: path("M33.799 11.01c0-1.434-.846-2.596-1.886-2.596c-1.039 0-1.886 1.162-1.886 2.596v21.04c0 1.436.848 2.6 1.886 2.6c1.041 0 1.886-1.164 1.886-2.6z");
}

</style>
