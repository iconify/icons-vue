<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xrd8umbxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:water-medium-rounded" /></template>
<style>
.xrd8umbxj {
  fill: currentColor;
  d: path("M6.125 12.15q1.175-.575 2.438-.862T11.125 11q.75 0 1.488.1t1.462.3q1.25.35 1.913.475T17.4 12h.475l.875-8H5.25zm.85 9.85q-.775 0-1.338-.513T5 20.226l-1.75-16q-.1-.875.488-1.55T5.225 2h13.55q.9 0 1.488.675t.487 1.55l-1.75 16q-.075.75-.637 1.263T17.025 22z");
}

</style>
