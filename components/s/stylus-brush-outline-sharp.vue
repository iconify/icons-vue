<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dygi7ocjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:stylus-brush-outline-sharp" /></template>
<style>
.dygi7ocjg {
  fill: currentColor;
  d: path("M12 16q-2.5 0-4.25-1.737T6 9.95Q6 8.1 7.1 6.475t2.413-2.85t2.4-1.925L13 1q0 1.425.513 2.4t1.937 2.075q1.475 1.15 2.013 2.138T18 9.95q0 2.575-1.75 4.313T12 16m2.825-3.162Q16 11.675 16 9.95q0-.875-.425-1.537T14.175 7q-.775-.575-1.388-1.237T11.75 4.3q-1.975 1.625-2.863 3T8 9.95q0 1.725 1.175 2.888T12 14t2.825-1.162M4 21l1-3h14l1 3z");
}

</style>
