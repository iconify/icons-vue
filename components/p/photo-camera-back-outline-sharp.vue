<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rrqt0552i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:photo-camera-back-outline-sharp" /></template>
<style>
.rrqt0552i {
  fill: currentColor;
  d: path("M2 21V5h5.15L9 3h6l1.85 2H22v16zm2-2h16V7h-4.05l-1.825-2h-4.25L8.05 7H4zm2-2h12l-3.75-5l-3 4L9 13z");
}

</style>
