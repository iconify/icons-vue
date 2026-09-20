<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gsqif3bwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-lock-portrait-sharp" /></template>
<style>
.gsqif3bwk {
  fill: currentColor;
  d: path("M6 22V2h12.077v4.83H19v3.686h-.923V22zm3.23-6.346h5.54v-4.538h-.981v-1q0-.749-.511-1.26q-.51-.51-1.259-.51t-1.259.51t-.51 1.26v1H9.23zm1.79-4.539v-1q0-.425.287-.712t.712-.288t.713.288t.287.712v1z");
}

</style>
