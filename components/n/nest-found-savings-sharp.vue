<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k1e9flb-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:nest-found-savings-sharp" /></template>
<style>
.k1e9flb-r {
  fill: currentColor;
  d: path("m12 23l-3-3H3V2h18v18h-6zm0-7q2.15 0 3.575-1.5T17 11V6h-5Q9.975 6 8.488 7.425T7 11q0 .75.213 1.425t.587 1.25l-1.1 1.1l1.35 1.35l1.025-1q.675.425 1.4.65T12 16m-2.75-3.775l3.3-3.3l1.425 1.4l-3.4 3.325z");
}

</style>
