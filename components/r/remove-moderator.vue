<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vi35sp_lw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:remove-moderator" /></template>
<style>
.vi35sp_lw {
  fill: currentColor;
  d: path("M18.85 16.05L6.8 3.95L12 2l8 3v6.1q0 1.275-.288 2.525t-.862 2.425m.95 6.55l-3.25-3.25q-.95.975-2.113 1.638T12 22q-3.475-.875-5.738-3.988T4 11.1V6.8L1.4 4.2l1.4-1.4l18.4 18.4z");
}

</style>
