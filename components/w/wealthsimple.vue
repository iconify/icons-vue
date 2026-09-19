<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="swvxs6bbq"/><path class="lgss5ccob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wealthsimple" /></template>
<style>
.lgss5ccob {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m33.93 28.835l-5.112-12.682c-.622-1.633-.356-3.09 2.456-3.9H18.982c2.023 1.2 2.756 2.811 2.9 3.256l2.046 5.035l-4.068 8.469l-5.413-13.515c-.611-1.634.411-3.012 1.823-3.246l-11.77.134c2.7 1.089 2.79 2.511 3.734 4.523l8.353 18.883l3.273-6.78");
}

.swvxs6bbq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m23.928 20.555l6.724 15.237l9.114-18.894q1.455-2.812 3.734-4.568l-8.447-.122c1.567 1.4 4.713 1.878.1 14.248");
}

</style>
