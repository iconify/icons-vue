<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lvsq4cc8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-caret-right-fill" /></template>
<style>
.lvsq4cc8t {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18 2C20.2091 2 22 3.79086 22 6V18C22 20.2091 20.2091 22 18 22H6C3.79086 22 2 20.2091 2 18V6C2 3.79086 3.79086 2 6 2H18ZM8.58301 6.10254C7.59119 5.71039 6.50014 6.45591 6.5 7.53809V16.4619C6.50015 17.6161 7.74116 18.3871 8.7793 17.8037L16.7168 13.3418C17.7611 12.7548 17.7611 11.2452 16.7168 10.6582L8.7793 6.19629L8.58301 6.10254Z");
}

</style>
