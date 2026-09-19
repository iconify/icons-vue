<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="axj08xfgf"/><path class="e1yq_jbjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:physics-wallah" /></template>
<style>
.axj08xfgf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.625 25.54v-15.2h4.195a4.357 4.357 0 1 1 0 8.714h-4.196m8.133 5.558l3.227 12.91l3.227-12.91l3.228 12.91l3.227-12.91");
}

.e1yq_jbjx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M2.88 18.706A21.866 21.866 0 0 1 34.932 5.43M13.067 42.57a21.866 21.866 0 0 0 32.054-13.276");
}

</style>
