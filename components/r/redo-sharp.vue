<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t4kj9iv0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:redo-sharp" /></template>
<style>
.t4kj9iv0y {
  fill: currentColor;
  d: path("M9.342 18q-1.963 0-3.355-1.364t-1.39-3.309t1.39-3.3Q7.38 8.673 9.343 8.673h7.743L14.12 5.708L14.828 5L19 9.173l-4.173 4.173l-.708-.707l2.966-2.966H9.342q-1.556 0-2.65 1.058q-1.096 1.058-1.096 2.596t1.095 2.606Q7.787 17 9.342 17h7.254v1z");
}

</style>
