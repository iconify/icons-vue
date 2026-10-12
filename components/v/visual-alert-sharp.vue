<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="b58yrdbot"/><path class="tb6q2fbtf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:visual-alert-sharp" /></template>
<style>
.b58yrdbot {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.41 3.38l1.19 1.81l.41.63l.7-.27l2.03-.77l.7-.26l-.04.75l-.1 2.16l-.04.75l.72.2l2.09.56l.73.2l-.47.59l-1.36 1.69l-.47.58l.47.58l1.36 1.69l.47.59l-.73.2l-2.09.56l-.72.2l.04.75l.1 2.16l.04.75l-.7-.26l-2.03-.77l-.7-.27l-.41.63l-1.19 1.81l-.41.63l-.41-.63l-1.19-1.81l-.41-.63l-.7.27l-2.03.77l-.7.26l.04-.75l.1-2.16l.04-.75l-.72-.2l-2.09-.56l-.73-.2l.47-.59l1.36-1.69l.47-.58l-.47-.58l-1.36-1.69l-.47-.59l.73-.2l2.09-.56l.72-.2l-.04-.75l-.1-2.16l-.04-.75l.7.26l2.03.77l.7.27l.41-.63l1.19-1.81l.41-.63zM12 8v4.5");
}

.tb6q2fbtf {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 15.75h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
