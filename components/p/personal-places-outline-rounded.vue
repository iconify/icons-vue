<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="biqf4wbbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:personal-places-outline-rounded" /></template>
<style>
.biqf4wbbj {
  fill: currentColor;
  d: path("M6 20V6q0-.825.588-1.412T8 4h7.45q.5 0 .925.225t.7.625l2.125 3q.35.525.35 1.15t-.35 1.15l-2.125 3q-.275.4-.7.625T15.45 14H8v6q0 .425-.288.713T7 21t-.712-.288T6 20m2-8h7.5l2-3l-2-3H8zm0 0V6z");
}

</style>
