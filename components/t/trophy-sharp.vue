<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vaw-o19ci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:trophy-sharp" /></template>
<style>
.vaw-o19ci {
  fill: currentColor;
  d: path("M8.385 20v-1H11.5v-3.754q-1.283-.102-2.36-1.047q-1.079-.945-1.317-2.21q-1.586-.187-2.705-1.301T4 8V6h3.654V4h8.692v2H20v2q0 1.573-1.118 2.688t-2.705 1.3q-.238 1.266-1.316 2.211T12.5 15.246V19h3.116v1zm-.731-9.084V7H5v1q0 1.142.762 1.963t1.892.953m8.692 0q1.131-.133 1.893-.954T19 8V7h-2.654z");
}

</style>
