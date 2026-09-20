<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z9vf9zb7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:sd-card-sharp" /></template>
<style>
.z9vf9zb7r {
  fill: currentColor;
  d: path("M4 22V8l6-6h10v20zm5-11h2V7H9zm3 0h2V7h-2zm3 0h2V7h-2z");
}

</style>
