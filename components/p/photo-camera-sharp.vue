<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l0cdlpbsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:photo-camera-sharp" /></template>
<style>
.l0cdlpbsg {
  fill: currentColor;
  d: path("M12 17.5q1.875 0 3.188-1.312T16.5 13t-1.312-3.187T12 8.5T8.813 9.813T7.5 13t1.313 3.188T12 17.5m0-2q-1.05 0-1.775-.725T9.5 13t.725-1.775T12 10.5t1.775.725T14.5 13t-.725 1.775T12 15.5M2 21V5h5.15L9 3h6l1.85 2H22v16z");
}

</style>
