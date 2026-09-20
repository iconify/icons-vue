<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oy5ehnoci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:sports-cricket-sharp" /></template>
<style>
.oy5ehnoci {
  fill: currentColor;
  d: path("M11.5 17.7L1.625 7.825l4.2-4.2L15.7 13.5zm7.1 4.3l-4.25-4.25l1.4-1.4L20 20.6zM16.025 7.975Q15 6.95 15 5.5t1.025-2.475T18.5 2t2.475 1.025T22 5.5t-1.025 2.475T18.5 9t-2.475-1.025");
}

</style>
