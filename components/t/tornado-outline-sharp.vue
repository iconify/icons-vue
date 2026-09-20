<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mitvq_bxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:tornado-outline-sharp" /></template>
<style>
.mitvq_bxp {
  fill: currentColor;
  d: path("M2.73 4h18.54L12 20zm1.745 1l2.033 3.5h10.984L19.525 5zm2.612 4.5l2.302 4h5.223l2.301-4zm2.88 5L12 18l2.033-3.5z");
}

</style>
