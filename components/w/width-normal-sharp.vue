<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xi8enmbzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:width-normal-sharp" /></template>
<style>
.xi8enmbzu {
  fill: currentColor;
  d: path("M2 20V4h20v16zm2-2h4V6H4zm12 0h4V6h-4z");
}

</style>
