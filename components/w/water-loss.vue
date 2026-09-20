<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cdiet8beo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:water-loss" /></template>
<style>
.cdiet8beo {
  fill: currentColor;
  d: path("M6.45 15q1.125-.5 2.3-.75t2.375-.25q.75 0 1.488.1t1.462.3q1.25.35 1.913.475T17.4 15h.15l1.2-11H5.25zm.525 7q-.775 0-1.337-.5T5 20.225L3 2h18l-2 18.225q-.075.775-.638 1.275t-1.337.5z");
}

</style>
