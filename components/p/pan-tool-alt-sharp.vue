<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y4vgbltvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:pan-tool-alt-sharp" /></template>
<style>
.y4vgbltvs {
  fill: currentColor;
  d: path("m9.275 20l-6.471-7.825l1.083-.95L8 13.787V2.98h1v8.558h2.673V6h1v5.539h2.673V7.191h1v4.347H19V9h1v11z");
}

</style>
