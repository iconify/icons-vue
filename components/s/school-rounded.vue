<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nh6ilvbre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:school-rounded" /></template>
<style>
.nh6ilvbre {
  fill: currentColor;
  d: path("M19.923 14.885V9.562l-7.146 3.875q-.373.211-.777.211t-.777-.212L4.388 9.702q-.217-.13-.32-.308T3.965 9t.103-.394t.32-.308l6.835-3.715q.187-.106.376-.159q.19-.053.401-.053t.401.053t.376.159l7.717 4.18q.212.106.32.305q.109.2.109.416v5.4q0 .214-.143.357q-.143.144-.357.144t-.357-.144t-.143-.357m-8.7 3.38L6.839 15.89q-.385-.218-.612-.597T6 14.461v-3.107l5.223 2.833q.373.211.777.211t.777-.212L18 11.354v3.108q0 .454-.227.832q-.227.379-.611.597l-4.385 2.373q-.186.105-.376.158t-.401.053t-.401-.053t-.376-.158");
}

</style>
