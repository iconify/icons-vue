<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mp_rw7b0q"/><path class="h3ty8tbnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-ad-units" /></template>
<style>
.h3ty8tbnv {
  fill: currentColor;
  d: path("M8 6h8v2H8z");
}

.mp_rw7b0q {
  fill: currentColor;
  d: path("M19 1H5v22h14zm-2 18H7V5h10z");
}

</style>
