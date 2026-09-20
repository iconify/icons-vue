<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nimow2b_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:stockpot-sharp" /></template>
<style>
.nimow2b_z {
  fill: currentColor;
  d: path("M3 20V8h18v12zM3 7V5h6V3h6v2h6v2z");
}

</style>
