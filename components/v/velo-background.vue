<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="uoux7wurf"/><path class="se416h2vf"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:velo-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.se416h2vf {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.593 17.647c-.736-.017-1.384-.262-1.91-.787c-1.945-1.959-3.908-3.9-5.87-5.859c-1.454-1.451-.876-3.9 1.086-4.511c1.034-.315 1.98-.088 2.752.682c1.945 1.923 3.855 3.847 5.782 5.77c.526.525.824 1.155.859 1.907c.052 1.242-.841 2.413-2.068 2.693c-.193.052-.42.07-.631.105m4.835-11.294A2.56 2.56 0 0 1 20 8.924a2.59 2.59 0 0 1-2.572 2.605c-1.42.017-2.588-1.169-2.605-2.588a2.605 2.605 0 0 1 2.605-2.588");
}

.uoux7wurf {
  fill: var(--svg-color--db2264, #db2264);
  d: path("M24 0H0v24h24z");
}

</style>
