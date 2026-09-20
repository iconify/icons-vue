<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wenbk8b0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:vignette-2" /></template>
<style>
.wenbk8b0m {
  fill: currentColor;
  d: path("M15.75 15.74q1.539-1.528 1.539-3.74T15.75 8.25T12 6.712T8.26 8.25T6.73 12t1.53 3.74q1.529 1.53 3.74 1.53t3.75-1.53M5.616 20q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h12.769q.69 0 1.153.463T20 5.616v12.769q0 .69-.462 1.153T18.384 20z");
}

</style>
