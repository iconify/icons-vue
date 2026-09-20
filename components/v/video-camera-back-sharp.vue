<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pwcy8ib3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:video-camera-back-sharp" /></template>
<style>
.pwcy8ib3y {
  fill: currentColor;
  d: path("M6.135 15.73h8.692l-2.758-3.653l-2.454 3.077l-1.588-1.885zM3.48 19V5h14v6.27l3.038-3.04v7.54l-3.038-3.04V19z");
}

</style>
