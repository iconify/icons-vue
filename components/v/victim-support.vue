<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o6a1iabhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:victim-support" /></template>
<style>
.o6a1iabhb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m6.22 11.28l5.25 5.25q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094l5.25-5.25q.1-.099.156-.228q1.31-2.972-1.215-5.016Q14.407 4.162 12 5.602q-2.407-1.44-4.721.434q-2.525 2.044-1.215 5.016q.056.129.156.228m14.656 3.345Q17.917 19.75 12 19.75t-8.876-5.125q-.075-.129-.095-.277q-.019-.148.02-.292q.038-.144.129-.263q.091-.118.22-.192q.064-.037.134-.061t.143-.034t.147-.004q.074.004.145.024q.071.019.138.051q.066.033.125.078t.107.1q.049.056.086.12Q6.948 18.25 12 18.25t7.577-4.375q.075-.129.193-.22t.263-.129q.144-.039.292-.02q.148.02.277.095q.064.036.12.085t.1.107q.045.059.078.125q.032.067.051.138q.02.071.024.145q.005.074-.004.147t-.034.143t-.061.134");
}

</style>
