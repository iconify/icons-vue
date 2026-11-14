<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="blee9jxrz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:piste-intermediate" /></template>
<style>
.blee9jxrz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8 1.75h8q1.76 0 3.005 1.245T20.25 6v7q0 1.76-1.245 3.005T16 17.25h-3.25v4.25q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-4.25H8q-1.76 0-3.005-1.245T3.75 13V6q0-1.76 1.245-3.005T8 1.75m9.25 11.441l-9.5-8.5q-.055-.049-.119-.087q-.063-.037-.133-.062q-.07-.024-.143-.035q-.073-.01-.147-.006q-.073.004-.145.023q-.071.018-.138.05t-.126.076t-.108.1t-.087.119t-.062.133t-.035.143t-.006.147t.023.145t.05.138t.076.126t.1.108l9.5 8.5q.111.099.252.149t.29.041t.283-.073t.234-.176q.049-.055.087-.119q.037-.063.062-.133q.024-.07.035-.143q.01-.073.006-.147q-.004-.073-.023-.145q-.018-.071-.05-.138t-.076-.126q-.045-.059-.1-.108");
}

</style>
