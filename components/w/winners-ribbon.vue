<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vtvig4bzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:winners-ribbon" /></template>
<style>
.vtvig4bzv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.75 9q0-3.003 2.123-5.127T12 1.75t5.127 2.123Q19.25 5.997 19.25 9t-2.123 5.127q-.421.421-.877.758V21.5q0 .24-.14.436q-.043.06-.096.111q-.054.05-.117.089t-.132.066q-.069.026-.142.038t-.146.01q-.074-.003-.146-.019q-.072-.017-.139-.047q-.068-.031-.128-.074L12 19.922L8.936 22.11q-.196.14-.436.14q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-6.615q-.456-.337-.877-.758Q4.75 12.003 4.75 9m3 0q0-1.76 1.245-3.005T12 4.75t3.005 1.245T16.25 9t-1.245 3.005T12 13.25t-3.005-1.245T7.75 9m1.5 6.733v4.31l2.314-1.653q.047-.034.1-.06q.052-.026.107-.044q.056-.018.113-.027q.058-.009.116-.009t.116.009t.113.027t.107.044t.1.06l2.314 1.653v-4.31q-1.268.517-2.75.517t-2.75-.517");
}

</style>
