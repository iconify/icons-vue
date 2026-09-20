<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qnjpmkbza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:pixel-3-3xl-3a-sharp" /></template>
<style>
.qnjpmkbza {
  fill: currentColor;
  d: path("M9 6q.425 0 .713-.287Q10 5.425 10 5t-.287-.713Q9.425 4 9 4t-.712.287Q8 4.575 8 5t.288.713Q8.575 6 9 6ZM5 23V1h14v22Z");
}

</style>
