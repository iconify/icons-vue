<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r8s8fbb6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:transit-enterexit-sharp" /></template>
<style>
.r8s8fbb6t {
  fill: currentColor;
  d: path("M6.73 17.385v-8.77H8.5v5.712l7.492-7.492l1.277 1.277l-7.503 7.504H15.5v1.769z");
}

</style>
