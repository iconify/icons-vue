<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uo_6-jb1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:polestar" /></template>
<style>
.uo_6-jb1f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m20.113 27.568l3.05 13.099l.837-.556V24H5.5l.208.541zM24 24l-3.887 3.568m7.774-7.136l-3.05-13.099l-.837.556V24h18.5l-.208-.541zM24 24l3.887-3.568");
}

</style>
