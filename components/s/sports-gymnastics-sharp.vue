<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b1glrbcvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sports-gymnastics-sharp" /></template>
<style>
.b1glrbcvc {
  fill: currentColor;
  d: path("m12.48 21.5l-.191-9.75l-4.904-1.25H.923v-1h6.23l7.674-5.404l.646.756l-4.707 3.36l3.676.865l7.243-4.443l.584.689l-8 6.08l-.75 10.097zM6.193 7.692q-.698 0-1.195-.497T4.5 6t.497-1.195t1.195-.497t1.195.497T7.884 6t-.497 1.195t-1.195.497");
}

</style>
