<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r3iawabfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:presale" /></template>
<style>
.r3iawabfu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4 1.75Q1.75 1.75 1.75 4v7q0 .149.057.287t.163.243l9.5 9.5q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094l.282-.282Q12 19.542 12 18q0-2.071 1.464-3.536Q14.929 13 17 13h2q.727 0 1.38.181l.65-.651q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113l-9.5-9.5q-.105-.106-.243-.163T11 1.75zM4.75 7q0-2.25 2.25-2.25T9.25 7T7 9.25T4.75 7M17 14.25q-3.75 0-3.75 3.75T17 21.75h2q3.75 0 3.75-3.75T19 14.25zM14.75 18q0-2.25 2.25-2.25T19.25 18T17 20.25T14.75 18m6.5 0q0 1.371-.835 1.906q.335-.785.335-1.906t-.335-1.906q.835.535.835 1.906m-5.144-.546l.348-.348q-.234.114-.348.348");
}

</style>
