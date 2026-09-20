<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rcq66ibnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:stockpot-outline-sharp" /></template>
<style>
.rcq66ibnx {
  fill: currentColor;
  d: path("M3 20V8h18v12zm2-2h14v-8H5zM3 7V5h6V3h6v2h6v2zm9 7");
}

</style>
