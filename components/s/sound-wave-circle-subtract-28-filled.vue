<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="f7houubbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:sound-wave-circle-subtract-28-filled" /></template>
<style>
.f7houubbb {
  fill: currentColor;
  d: path("M20.5 14a6.5 6.5 0 1 1 0 13a6.5 6.5 0 0 1 0-13M14 2c6.627 0 12 5.373 12 12q0 .672-.073 1.325A7.48 7.48 0 0 0 20 13.02V9.75a.75.75 0 0 0-1.5 0v3.521a7.5 7.5 0 0 0-2 .886V11.75a.75.75 0 0 0-1.5 0v3.652a7.47 7.47 0 0 0-2 5.098a7.48 7.48 0 0 0 2.325 5.427q-.653.072-1.325.073C7.373 26 2 20.627 2 14S7.373 2 14 2m2.5 18a.5.5 0 0 0 0 1h8a.5.5 0 0 0 0-1zM12.25 9a.75.75 0 0 0-.75.75v8.5a.75.75 0 0 0 1.5 0v-8.5a.75.75 0 0 0-.75-.75m-3.5 2.5a.75.75 0 0 0-.75.75v3.5a.75.75 0 0 0 1.5 0v-3.5a.75.75 0 0 0-.75-.75");
}

</style>
