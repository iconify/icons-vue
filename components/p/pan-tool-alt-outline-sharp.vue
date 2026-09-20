<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="awytgpasd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:pan-tool-alt-outline-sharp" /></template>
<style>
.awytgpasd {
  fill: currentColor;
  d: path("m9.275 20l-6.471-7.825l1.083-.95L8 13.787V2.98h1v12.675l-4.217-2.642L9.763 19H19V9h1v11zm2.398-8V6h1v6zm3.673 0V7.192h1V12zm-1.384 3.27");
}

</style>
