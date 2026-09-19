<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k4ndmyb7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sweech" /></template>
<style>
.k4ndmyb7s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m36.276 24l-5.846-5.848L42.5 6.077H11.323l-5.089 5.09v7.343l5.49 5.49m18.706-5.848l-6.146-6.148M11.724 24l5.846 5.848L5.5 41.923h31.177l5.088-5.09V29.49L36.277 24M17.57 29.848l6.146 6.148");
}

</style>
