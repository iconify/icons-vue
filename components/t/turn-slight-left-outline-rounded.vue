<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v-e1yr4mb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:turn-slight-left-outline-rounded" /></template>
<style>
.v-e1yr4mb {
  fill: currentColor;
  d: path("M13.288 19.713Q13 19.425 13 19v-6.6l-5-5v1.25q0 .425-.288.713T7 9.65t-.712-.288T6 8.65V5q0-.425.288-.712T7 4h3.65q.425 0 .713.288T11.65 5t-.288.713T10.65 6H9.4l5.025 5.025q.275.275.425.638t.15.762V19q0 .425-.287.713T14 20t-.712-.288");
}

</style>
