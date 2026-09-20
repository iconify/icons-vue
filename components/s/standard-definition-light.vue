<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="h834ftaab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:standard-definition-light" /></template>
<style>
.h834ftaab {
  fill: currentColor;
  d: path("M144 74a6 6 0 0 0-6 6v96a6 6 0 0 0 6 6h24a54 54 0 0 0 0-108Zm66 54a42 42 0 0 1-42 42h-18V86h18a42 42 0 0 1 42 42M26 48a6 6 0 0 1 6-6h192a6 6 0 0 1 0 12H32a6 6 0 0 1-6-6m204 160a6 6 0 0 1-6 6H32a6 6 0 0 1 0-12h192a6 6 0 0 1 6 6m-124-56c0-11.21-10.7-15.1-28.33-20.18c-15.89-4.58-33.89-9.77-33.89-27.82c0-17.1 15.57-30 36.22-30c15 0 27.74 6.88 33.34 18a6 6 0 0 1-10.71 5.42C99.08 90.36 90.41 86 80 86c-13.81 0-24.22 7.74-24.22 18c0 8.41 9.52 11.76 25.21 16.29C97.48 125 118 131 118 152c0 16.54-17 30-38 30s-38-13.46-38-30a6 6 0 0 1 12 0c0 9.76 11.91 18 26 18s26-8.24 26-18");
}

</style>
