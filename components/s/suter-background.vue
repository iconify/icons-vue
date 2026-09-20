<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mdeekac-w"/><path class="qr2mk7b8l"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:suter-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mdeekac-w {
  fill: var(--svg-color--38276d, #38276d);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qr2mk7b8l {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.609 10.347a.867.867 0 0 1 0-1.225l4.863-4.868a.866.866 0 1 1 1.224 1.225l-4.863 4.868a.863.863 0 0 1-1.224 0m8.781 3.307a.867.867 0 0 1 0 1.225l-4.862 4.867a.866.866 0 1 1-1.224-1.225l4.863-4.868a.87.87 0 0 1 .943-.187q.159.065.28.188m-9.095 1.039a.867.867 0 0 1 0-1.225l3.078-3.082a.867.867 0 0 1 1.224 0a.867.867 0 0 1 0 1.226L8.52 14.693a.866.866 0 0 1-1.224 0m9.409-5.386a.867.867 0 0 1 0 1.225l-3.079 3.081a.866.866 0 1 1-1.224-1.225l3.078-3.081a.866.866 0 0 1 1.224 0");
}

</style>
