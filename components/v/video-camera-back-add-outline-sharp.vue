<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fq08hrf7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:video-camera-back-add-outline-sharp" /></template>
<style>
.fq08hrf7e {
  fill: currentColor;
  d: path("M3.48 19v-6.615h1V18h12V6h-5.614V5h6.615v6.27l3.038-3.04v7.54l-3.038-3.04V19zm2.655-3.27h8.692l-2.74-3.653l-2.53 3.192l-1.605-1.925zM5.48 10V8h-2V7h2V5h1v2h2v1h-2v2z");
}

</style>
