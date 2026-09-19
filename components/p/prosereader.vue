<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pzok88beu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:prosereader" /></template>
<style>
.pzok88beu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.7 4.5h-2.3c-1.1 0-2 .9-2 2v35c0 1.1.9 2 2 2h2.3m0-39v39h24.9c1.1 0 2-.9 2-2v-35c0-1.1-.9-2-2-2zm6.1 16.8h14.7m-14.7 5.4h10");
}

</style>
