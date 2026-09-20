<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="tn77d5b5d"/><path class="dwsi9i-cp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:polx" /></template>
<style>
.bi12bsetm {
  fill: none;
  fill-rule: evenodd;
}

.dwsi9i-cp {
  fill: var(--svg-color--457cd6, #457cd6);
  d: path("M4.543 11.25L3 17.75l4.587-3H17.5a3.5 3.5 0 0 0 3.499-3.5z");
}

.tn77d5b5d {
  fill: var(--svg-color--86e7f7, #86e7f7);
  d: path("M4.534 11.25L3 17.75l4.678-3.079H17.5a3.5 3.5 0 0 0 3.499-3.42zm.353-1.5H21v-.5a3 3 0 0 0-3-3H5.728v.059l-.015-.059z");
}

</style>
