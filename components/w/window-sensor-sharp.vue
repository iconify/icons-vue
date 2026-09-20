<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y2dy4rhle"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:window-sensor-sharp" /></template>
<style>
.y2dy4rhle {
  fill: currentColor;
  d: path("M21.143 8.856Q21 8.713 21 8.5v-4q0-.213.144-.356T21.501 4t.356.144T22 4.5v4q0 .213-.144.356T21.499 9t-.356-.144M4 20V4h14v16zm1.77-8.5h4.46v-.77h1.54v.77h4.46V5.77H5.77zm0 6.73h10.46V12.5H5.77zM5 19h12V5H5z");
}

</style>
