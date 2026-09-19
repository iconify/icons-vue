<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gdpln8f6s"/><path class="kuq0q0blp"/><path class="bkizwacyv"/><path class="bbomzvb3v"/><path class="y6vvl3bgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:stylish-text" /></template>
<style>
.bbomzvb3v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.266 27.85c-.664-.063-1.299-.115-1.875-.167a20 20 0 0 1-1.668-.217");
}

.bkizwacyv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.243 33.958C5.63 27.716 4.45 40.525 12.906 40.7c7.095.149 20.035-2.462 20.406-8.344c.213-3.364-4.978-4.127-9.046-4.507");
}

.gdpln8f6s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.29 36.825a.627.627 0 0 1 .872-.163l.002.002l1.55 1.066a.627.627 0 0 1 .162.871l-.002.003l-2.346.643zM36.533 5.608l1.55 1.066a.627.627 0 0 1 .161.871v.002L37.188 9.08a.627.627 0 0 1-.871.162l-.003-.002l-1.549-1.066a.627.627 0 0 1-.161-.871V7.3l1.054-1.533a.627.627 0 0 1 .872-.162zm-2.736 3.974l1.55 1.065a.627.627 0 0 1 .162.872l-.002.003L18.555 36.16a.627.627 0 0 1-.872.161q0 0 0 0l-1.55-1.065a.627.627 0 0 1-.162-.872l.001-.002l16.953-24.64a.627.627 0 0 1 .873-.16zm-1.371.788c-1.935-2.08-3.375-3.403-6.729-4.77c-1.53.033-4.136 1.085-6.206 3.564c-1.418 1.7-2.06 3.415-1.932 4.98");
}

.kuq0q0blp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.28 20.564c3.735.505 7.826 1.65 9.868 4.815c3.097 4.799 1.647 12.695-5.805 16.195c-3.13 1.47-5.657 1.045-7.13-.21c-4.967-4.228-4.89-3.977-7.197-5.55");
}

.y6vvl3bgu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.723 27.467C9.358 25.483 10.616 14.649 17.56 14.143c.231 2.826 2.978 5.158 8.203 6.001");
}

</style>
