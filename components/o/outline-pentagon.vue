<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bah_1ol8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-pentagon" /></template>
<style>
.bah_1ol8l {
  fill: currentColor;
  d: path("M19.63 9.78L16.56 19H7.44L4.37 9.78L12 4.44zM2 9l4 12h12l4-12l-10-7z");
}

</style>
