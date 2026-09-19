<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dtj_11zna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-ice-skating" /></template>
<style>
.dtj_11zna {
  fill: currentColor;
  d: path("M21 17c0 1.66-1.34 3-3 3h-2v-2h3l-.01-6l-5.71-1.43A3 3 0 0 1 11.32 9H8V8h3.02L11 7H8V6h3V3H3v15h3v2H2v2h16c2.76 0 5-2.24 5-5zm-7 3H8v-2h6z");
}

</style>
