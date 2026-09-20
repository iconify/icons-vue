<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e19_m6s4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:villa-sharp" /></template>
<style>
.e19_m6s4m {
  fill: currentColor;
  d: path("M9 21v-9h8q0-.825.588-1.412T19 10t1.413.588T21 12v9h-5v-5h-2v5zm-6 0V8l13-5v7H7v11z");
}

</style>
