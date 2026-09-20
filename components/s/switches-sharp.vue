<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nit7-xu8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:switches-sharp" /></template>
<style>
.nit7-xu8j {
  fill: currentColor;
  d: path("M7.385 16q-1.671 0-2.836-1.164Q3.384 13.67 3.384 12T4.55 9.165T7.384 8q1.135 0 2.042.55t1.42 1.45h9.77v4h-9.77q-.513.9-1.42 1.45T7.385 16m3.861-3h8.37v-2h-8.37q.07.225.104.5t.035.5t-.035.5t-.104.5");
}

</style>
