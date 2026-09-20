<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qhgw6viar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:replay-10-sharp" /></template>
<style>
.qhgw6viar {
  fill: currentColor;
  d: path("M8.882 20.374q-1.455-.626-2.542-1.713t-1.714-2.543T4 13h1q0 2.925 2.038 4.963T12 20t4.963-2.037T19 13t-2.037-4.962T12 6h-.38l1.626 1.627l-.708.72L9.692 5.48l2.885-2.866l.708.72L11.619 5H12q1.664 0 3.118.626T17.66 7.34t1.714 2.542T20 13t-.626 3.118t-1.714 2.543t-2.542 1.713T12 21t-3.118-.626m.541-4.682v-4.5H8.039v-.884h2.269v5.384zm2.27 0v-5.384h3.769v5.384zm.884-.884h2v-3.616h-2z");
}

</style>
