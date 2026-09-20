<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rz3wm8ehv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:split-scene-left" /></template>
<style>
.rz3wm8ehv {
  fill: currentColor;
  d: path("M14.885 19V5h3.5q.69 0 1.153.463T20 6.616v10.769q0 .69-.462 1.153T18.384 19zM11.5 21v-2H5.616q-.691 0-1.153-.462T4 17.384V6.616q0-.691.463-1.153T5.616 5H11.5V3h1v18z");
}

</style>
