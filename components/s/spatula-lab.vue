<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gcgmgxu7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:spatula-lab" /></template>
<style>
.gcgmgxu7v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.222 17.657l3.182-3.182l2.121 2.121l-3.182 3.182Zm4.242-2.121l4.243-4.243m-1.768-1.768l6.011-6.01l3.535 3.535l-6.01 6.011Z");
}

</style>
