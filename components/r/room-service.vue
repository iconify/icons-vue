<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vyyhq72mp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:room-service" /></template>
<style>
.vyyhq72mp {
  fill: currentColor;
  d: path("M2 19v-2h20v2zm1-3v-1q0-3.2 1.963-5.65T10 6.25V6q0-.825.588-1.412T12 4t1.413.588T14 6v.25q3.1.65 5.05 3.1T21 15v1z");
}

</style>
