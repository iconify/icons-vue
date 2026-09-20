<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h74pwob-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:nfc-sharp" /></template>
<style>
.h74pwob-r {
  fill: currentColor;
  d: path("M7 17h10V7h-4q-.825 0-1.412.588T11 9v1.3q-.5.275-.75.7T10 12q0 .825.588 1.413T12 14t1.413-.587T14 12q0-.575-.275-1T13 10.3V9h2v6H9V9h1V7H7zm-4 4V3h18v18z");
}

</style>
