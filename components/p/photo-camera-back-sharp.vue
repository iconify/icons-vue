<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qd_h5fbka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:photo-camera-back-sharp" /></template>
<style>
.qd_h5fbka {
  fill: currentColor;
  d: path("M2 21V5h5.15L9 3h6l1.85 2H22v16zm4-4h12l-3.75-5l-3 4L9 13z");
}

</style>
