<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o2p8znbwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:smartphone-camera-sharp" /></template>
<style>
.o2p8znbwv {
  fill: currentColor;
  d: path("M5 23V1h14v5H7v12h12v5zm8-7V9h2.5l1-1h2l1 1H22v7zm4.5-1.75q.725 0 1.238-.513t.512-1.237t-.513-1.237t-1.237-.513t-1.237.513t-.513 1.237t.513 1.238t1.237.512");
}

</style>
