<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="obui2lbes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:send-outline-rounded" /></template>
<style>
.obui2lbes {
  fill: currentColor;
  d: path("m19.8 12.925l-15.4 6.5q-.5.2-.95-.088T3 18.5v-13q0-.55.45-.837t.95-.088l15.4 6.5q.625.275.625.925t-.625.925M5 17l11.85-5L5 7v3.5l6 1.5l-6 1.5zm0 0V7z");
}

</style>
