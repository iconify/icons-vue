<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="rpdzbf-su"/><path class="oho_vmbzf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shield-off-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.oho_vmbzf {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 3h8a2 2 0 0 1 2 2v5c0 .958-.106 1.855-.305 2.695m-1.952 4.048C16.3 18.59 14.279 19.987 12 21c-4.5-2-8-5.5-8-11V5c0-.552.224-1.052.586-1.414M3 2l19 19");
}

.rpdzbf-su {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M10 3h8a2.003 2.003 0 0 1 2 2v5a11.6 11.6 0 0 1-.305 2.695Zm7.743 13.743C16.254 18.648 14.192 20.025 12 21c-4.676-2.082-7.994-5.653-8-11V5c0-.535.205-1.038.586-1.414Z");
}

</style>
