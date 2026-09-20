<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p4uos7z4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:wifi" /></template>
<style>
.p4uos7z4p {
  fill: currentColor;
  d: path("M10.908 19.977q-.446-.446-.446-1.092t.446-1.093T12 17.346t1.092.446t.446 1.093t-.446 1.092t-1.092.446t-1.092-.446M6.35 15.35l-1.023-1.034q1.302-1.302 3.001-2.04q1.699-.737 3.672-.737t3.672.74t3.001 2.048L17.65 15.35q-1.1-1.1-2.55-1.725T12 13t-3.1.625t-2.55 1.725M2.1 11.1l-1.023-1.023q2.089-2.1 4.875-3.32T12 5.54t6.048 1.219t4.875 3.319L21.9 11.1q-1.925-1.925-4.462-3.012T12 7T6.563 8.088T2.1 11.1");
}

</style>
