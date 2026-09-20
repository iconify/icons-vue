<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nqf4s-byp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:process-chart-rounded" /></template>
<style>
.nqf4s-byp {
  fill: currentColor;
  d: path("M2.63 17.558q-.182-.085-.252-.29t.014-.387l5.12-10.22q.084-.182.28-.243q.195-.06.377.024q.183.085.253.29t-.014.387l-5.12 10.22q-.084.182-.28.243q-.194.06-.377-.024m5.77-.29q-.07-.205.014-.387l5.12-10.22q.084-.182.28-.243q.194-.06.377.024q.183.085.253.29t-.014.387L9.31 17.34q-.084.182-.28.243t-.377-.024t-.253-.29m6.023 0q-.07-.205.014-.387l5.12-10.22q.084-.182.28-.243t.377.024t.253.29t-.014.387l-5.12 10.22q-.084.182-.28.243t-.377-.024q-.183-.085-.253-.29");
}

</style>
