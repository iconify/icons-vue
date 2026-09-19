<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f3dg35b7o"/><path class="fr8djqb8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ov-plus" /></template>
<style>
.f3dg35b7o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.218 8.018a.97.97 0 0 0-.866-.532H6.473a.972.972 0 0 0-.867 1.412L13.27 24L5.606 39.102a.972.972 0 0 0 .867 1.412h9.878a.97.97 0 0 0 .867-.532L25.328 24z");
}

.fr8djqb8g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.39 8.018a.97.97 0 0 0-.866-.532h-9.879a.972.972 0 0 0-.866 1.412L30.442 24l-7.663 15.102a.972.972 0 0 0 .866 1.412h9.879a.97.97 0 0 0 .867-.532L42.5 24z");
}

</style>
