<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r6xlfhjah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:room-service-rounded" /></template>
<style>
.r6xlfhjah {
  fill: currentColor;
  d: path("M3 19q-.425 0-.712-.288T2 18t.288-.712T3 17h18q.425 0 .713.288T22 18t-.288.713T21 19zm0-3v-1q0-3.2 1.963-5.65T10 6.25V6q0-.825.588-1.412T12 4t1.413.588T14 6v.25q3.1.65 5.05 3.1T21 15v1z");
}

</style>
