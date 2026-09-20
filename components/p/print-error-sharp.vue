<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w4aqs1rbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:print-error-sharp" /></template>
<style>
.w4aqs1rbp {
  fill: currentColor;
  d: path("M18.48 19.79q-.21-.21-.21-.52t.21-.521q.209-.21.52-.21t.52.21t.21.52t-.21.52Q19.312 20 19 20t-.52-.21m.02-4.02v-4h1v4zM7 20v-4H3.577V8.616h16.556v1h-4.017v4.846H8V19h8.116v1zM7 7.846v-3.23h10v3.23z");
}

</style>
