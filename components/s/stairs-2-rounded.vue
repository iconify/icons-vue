<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kcl1kybcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:stairs-2-rounded" /></template>
<style>
.kcl1kybcf {
  fill: currentColor;
  d: path("M3.5 18q-.213 0-.356-.144T3 17.499t.144-.356T3.5 17h5.173v-4.692q0-.343.232-.576t.576-.232h4.846V6.808q0-.343.232-.576T15.134 6H20.5q.213 0 .356.144t.144.357t-.144.356T20.5 7h-5.173v4.692q0 .344-.232.576t-.576.232H9.673v4.692q0 .344-.232.576T8.866 18z");
}

</style>
