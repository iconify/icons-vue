<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="as9ll-bzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:person-raised-hand-sharp" /></template>
<style>
.as9ll-bzn {
  fill: currentColor;
  d: path("M2 23v-2h20v2zm2-3v-6q-.825-1.35-1.275-2.863t-.45-3.087q0-1.525.388-3t.912-2.9q.2-.525.65-.837t1-.313Q6 1 6.55 1.525T7 2.775L6.725 5.05q-.15 1.2.213 2.275t1.087 1.887t1.75 1.3T12 11q1.5 0 3.013.313t2.637.887t1.738 1.463T20 15.85V20H10v-.925q0-.85.575-1.463T12 17h4v-2h-4q-1.675 0-2.838 1.2T8 19.075V20zM9.175 8.825Q8 7.65 8 6t1.175-2.825T12 2t2.825 1.175T16 6t-1.175 2.825T12 10T9.175 8.825");
}

</style>
