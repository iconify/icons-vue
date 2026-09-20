<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bz71ejtwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:workspace-premium" /></template>
<style>
.bz71ejtwc {
  fill: currentColor;
  d: path("m9.925 13.277l.779-2.58l-2.05-1.505h2.562L12 6.585l.785 2.607h2.561l-2.056 1.504l.78 2.581L12 11.675zM7 21.462v-6.59q-.95-.935-1.475-2.19Q5 11.43 5 10q0-2.927 2.036-4.963T12 3t4.964 2.036T19 10q0 1.429-.525 2.683T17 14.87v6.59l-5-1.5zm9.25-7.212Q18 12.5 18 10t-1.75-4.25T12 4T7.75 5.75T6 10t1.75 4.25T12 16t4.25-1.75");
}

</style>
