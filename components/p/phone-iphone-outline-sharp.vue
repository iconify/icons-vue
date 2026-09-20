<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ll40_xnax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:phone-iphone-outline-sharp" /></template>
<style>
.ll40_xnax {
  fill: currentColor;
  d: path("M5 23V1h14v22zm2-5v3h10v-3zm5 2.5q.425 0 .713-.288T13 19.5t-.288-.712T12 18.5t-.712.288T11 19.5t.288.713t.712.287M7 16h10V6H7zM7 4h10V3H7zm0 14v3zM7 4V3z");
}

</style>
