<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lf_tcybnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:signal-cellular-off-outline-sharp" /></template>
<style>
.lf_tcybnt {
  fill: currentColor;
  d: path("M5.421 20H18.58L12 13.421zm15.566 2.408L19.579 21H3l8.292-8.292L3.65 5.07l.708-.713L21.7 21.7zM21 18.194l-1-1V5.421l-5.886 5.887l-.714-.708L21 3zm-5.708-1.486");
}

</style>
