<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fkuzi3b9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-roller-shades" /></template>
<style>
.fkuzi3b9r {
  fill: currentColor;
  d: path("M20 19V3H4v16H2v2h20v-2zM18 5v6H6V5zM6 19v-6h5v1.82A1.746 1.746 0 0 0 12 18a1.746 1.746 0 0 0 1-3.18V13h5v6z");
}

</style>
