<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="os37_ibtk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pyramid-fill-round" /></template>
<style>
.os37_ibtk {
  fill: currentColor;
  d: path("m2.277 17.781l8.891-13.336a1 1 0 0 1 1.664 0l8.891 13.336A2.071 2.071 0 0 1 20 21H4a2.069 2.069 0 0 1-1.723-3.219m1.664 1.11a.07.07 0 0 0-.003.072A.07.07 0 0 0 4 19h10.698L11.604 7.397Z");
}

</style>
