<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nww8_ob4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:sports-gymnastics-outline-sharp" /></template>
<style>
.nww8_ob4c {
  fill: currentColor;
  d: path("m12 22l-.5-10L8 11H1V9h6l7-5l1.3 1.525L11.15 8.5H14L21.8 4L23 5.4L14.5 12L14 22zM6 8q-.825 0-1.412-.587T4 6t.588-1.412T6 4t1.413.588T8 6t-.587 1.413T6 8");
}

</style>
