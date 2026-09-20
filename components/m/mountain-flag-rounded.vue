<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o3unjhbst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mountain-flag-rounded" /></template>
<style>
.o3unjhbst {
  fill: currentColor;
  d: path("m7.025 11.825l.825-1.7q.25-.525.738-.825T9.65 9H11V3q0-.425.288-.712T12 2h5.2q.275 0 .425.238t.025.487l-.55 1.05q-.05.125-.05.225t.05.225l.55 1.05q.125.25-.025.487T17.2 6H13v3h1.275q.575 0 1.038.3t.737.8l.875 1.75l-3 2L12 12.875l-1.925.975zM5.225 22q-1.125 0-1.712-.937t-.088-1.938l2.7-5.5l3.8 2.525L12 15.125l2.075 1.025l3.75-2.475L20.55 19.1q.5 1-.088 1.95T18.75 22z");
}

</style>
