<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l33rxh2cw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:switches-outline-sharp" /></template>
<style>
.l33rxh2cw {
  fill: currentColor;
  d: path("M7.385 16q-1.671 0-2.836-1.164Q3.384 13.67 3.384 12T4.55 9.165T7.384 8q1.126 0 2.037.55T10.846 10h9.77v4h-9.77q-.513.9-1.425 1.45T7.385 16m3.861-3h8.37v-2h-8.37q.07.225.104.5t.035.5t-.035.5t-.104.5M9.51 14.125q.875-.875.875-2.125T9.51 9.875T7.385 9t-2.125.875T4.385 12t.875 2.125T7.385 15t2.125-.875");
}

</style>
