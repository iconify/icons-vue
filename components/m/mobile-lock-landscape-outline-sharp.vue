<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="etxvwel8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-lock-landscape-outline-sharp" /></template>
<style>
.etxvwel8w {
  fill: currentColor;
  d: path("M9.23 15.654h5.54v-4.538h-.981v-1q0-.749-.511-1.26q-.51-.51-1.259-.51t-1.259.51t-.51 1.26v1H9.23zm1.79-4.538v-1q0-.425.287-.713t.712-.288t.713.288t.287.713v1zM2 18V5.923h4.83V5h3.686v.923H22V18zm19-1V6.923H3V17zM3 17V6.923z");
}

</style>
