<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="feurb_09b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:watch-lock-sharp" /></template>
<style>
.feurb_09b {
  fill: currentColor;
  d: path("M9.885 14.462v-3.808h.846v-.846q0-.53.37-.9t.899-.37t.899.37t.37.9v.846h.847v3.808zm1.586-3.808h1.058v-.846q0-.217-.156-.373T12 9.279t-.373.156t-.156.373zM9.961 21l-1.119-3.934q-1.258-.739-2.05-2.087T6 12t.792-2.979t2.05-2.087L9.962 3h4.077l1.119 3.935q1.258.738 2.05 2.086T18 12t-.792 2.979t-2.05 2.087L14.038 21zm5.577-5.462Q17 14.075 17 12t-1.463-3.537T12 7T8.463 8.463T7 12t1.463 3.538T12 17t3.538-1.463");
}

</style>
