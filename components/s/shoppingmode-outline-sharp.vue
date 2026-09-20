<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kthd73b_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:shoppingmode-outline-sharp" /></template>
<style>
.kthd73b_m {
  fill: currentColor;
  d: path("M11.975 22.825L2 12.85L12.8 2h10v10zm0-2.825l8.825-8.85V4h-7.15l-8.825 8.85zM18.3 8q.625 0 1.063-.437T19.8 6.5t-.437-1.062T18.3 5t-1.062.438T16.8 6.5t.438 1.063T18.3 8m-5.475 4");
}

</style>
