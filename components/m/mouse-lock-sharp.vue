<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ek3c31b8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mouse-lock-sharp" /></template>
<style>
.ek3c31b8c {
  fill: currentColor;
  d: path("M15 22v-5h1v-1q0-.825.588-1.412T18 14t1.413.588T20 16v1h1v5zm2-5h2v-1q0-.425-.288-.712T18 15t-.712.288T17 16zM5 9q0-2.625 1.7-4.587T11 2.074V9zm8 0V2.075q2.6.375 4.3 2.338T19 9zm-1 13q-2.925 0-4.962-2.037T5 15v-4h14v1.1q-.25-.05-.488-.075T18 12q-2.075 0-3.537 1.463T13 17v4.925q-.25.05-.488.063T12 22");
}

</style>
