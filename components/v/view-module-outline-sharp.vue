<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a55x48nvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:view-module-outline-sharp" /></template>
<style>
.a55x48nvq {
  fill: currentColor;
  d: path("M15.675 11H19V7h-3.325zm-5.35 0h3.325V7h-3.325zM5 11h3.325V7H5zm0 6h3.325v-4H5zm5.325 0h3.325v-4h-3.325zm5.35 0H19v-4h-3.325zM3 19V5h18v14z");
}

</style>
