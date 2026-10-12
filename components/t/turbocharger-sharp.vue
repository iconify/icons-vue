<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="sezmq5box"/><path class="x5qfiobox"/><path class="dmakavyej"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:turbocharger-sharp" /></template>
<style>
.dmakavyej {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11 13.5h.01");
}

.sezmq5box {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 6.75h10.25v5.75h-3.57A6.75 6.75 0 1 1 11 6.75Zm7.5 0v5.75");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.x5qfiobox {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m10.54 11.31l-.03-.52l-.03-.5h1.04l-.03.5l-.03.52l-.03.49l.41.24l.41.24l.42-.28l.43-.28l.42-.27l.25.43l.02.03l.25.43l-.45.23l-.46.23l-.45.23v.94l.45.23l.46.23l.45.23l-.25.43l-.02.03l-.25.43l-.42-.27l-.43-.28l-.42-.28l-.41.24l-.41.24l.03.49l.03.52l.03.5h-1.04l.03-.5l.03-.52l.03-.49l-.41-.24l-.41-.24l-.42.28l-.43.28l-.42.27l-.25-.43l-.02-.03l-.25-.43l.45-.23l.46-.23l.45-.23v-.94l-.45-.23l-.46-.23l-.45-.23l.25-.43l.02-.03l.25-.43l.42.27l.43.28l.42.28l.41-.24l.41-.24z");
}

</style>
