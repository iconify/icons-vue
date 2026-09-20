<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rh_qxd_ga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:tile-medium" /></template>
<style>
.rh_qxd_ga {
  fill: currentColor;
  d: path("M3 19v-6h8v6zm10 0v-6h8v6zM3 11V5h18v6z");
}

</style>
