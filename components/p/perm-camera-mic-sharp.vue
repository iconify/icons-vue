<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fvap3371m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:perm-camera-mic-sharp" /></template>
<style>
.fvap3371m {
  fill: currentColor;
  d: path("M2 21V5h5.15L9 3h6l1.85 2H22v16h-9v-3.1q2.2-.35 3.6-2.025T18 12h-2q0 1.65-1.175 2.825T12 16t-2.825-1.175T8 12H6q0 2.2 1.4 3.875T11 17.9V21zm10-7q.825 0 1.413-.587T14 12V8q0-.825-.587-1.412T12 6t-1.412.588T10 8v4q0 .825.588 1.413T12 14");
}

</style>
