<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mg8cs8b9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:portrait-lighting-rounded" /></template>
<style>
.mg8cs8b9w {
  fill: currentColor;
  d: path("M12 12q-1.65 0-2.825-1.175T8 8q0-1.65 1.175-2.825T12 4q1.65 0 2.825 1.175T16 8q0 1.65-1.175 2.825T12 12Zm-8 7v-1.8q0-.85.438-1.563T5.6 14.55q1.55-.775 3.15-1.163T12 13q1.65 0 3.25.388t3.15 1.162q.725.375 1.163 1.088T20 17.2V19q0 .425-.288.713T19 20H5q-.425 0-.713-.288T4 19Zm8-1h6v-.8q0-.275-.138-.5t-.362-.35q-1.35-.675-2.725-1.012T12 15v3Zm0-8q.825 0 1.413-.588T14 8q0-.825-.588-1.413T12 6v4Z");
}

</style>
