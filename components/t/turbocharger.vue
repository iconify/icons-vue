<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="q8_k_hjha"/><path class="tn5ts78ze"/><path class="dmakavyej"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:turbocharger" /></template>
<style>
.dmakavyej {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11 13.5h.01");
}

.q8_k_hjha {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 6.75h9.25a1 1 0 0 1 1 1v3.75a1 1 0 0 1-1 1h-2.57A6.75 6.75 0 1 1 11 6.75m7.5 0v5.75");
}

.tn5ts78ze {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m10.54 11.31l-.03-.52q-.03-.5.47-.5h.04q.5 0 .47.5l-.03.52q-.03.49.38.73t.83-.04l.43-.28q.42-.27.67.16l.02.03q.25.43-.2.66l-.46.23q-.45.23-.45.7t.45.7l.46.23q.45.23.2.66l-.02.03q-.25.43-.67.16l-.43-.28q-.42-.28-.83-.04t-.38.73l.03.52q.03.5-.47.5h-.04q-.5 0-.47-.5l.03-.52q.03-.49-.38-.73t-.83.04l-.43.28q-.42.27-.67-.16l-.02-.03q-.25-.43.2-.66l.46-.23q.45-.23.45-.7t-.45-.7l-.46-.23q-.45-.23-.2-.66l.02-.03q.25-.43.67-.16l.43.28q.42.28.83.04t.38-.73");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
