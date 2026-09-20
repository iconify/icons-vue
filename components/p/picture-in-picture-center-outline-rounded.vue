<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iuy3706im"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:picture-in-picture-center-outline-rounded" /></template>
<style>
.iuy3706im {
  fill: currentColor;
  d: path("M4 20q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4h16q.825 0 1.413.588T22 6v12q0 .825-.587 1.413T20 20zm0-2h16V6H4zm5-3h6q.425 0 .713-.288T16 14v-4q0-.425-.288-.712T15 9H9q-.425 0-.712.288T8 10v4q0 .425.288.713T9 15m-5 3V6z");
}

</style>
