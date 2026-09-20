<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zs_2libwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:vrpano-sharp" /></template>
<style>
.zs_2libwq {
  fill: currentColor;
  d: path("M3.006 19V5.033q1.99.644 4.144 1.075t4.856.43t4.856-.43t4.144-1.075V19q-1.99-.644-4.144-1.053t-4.856-.409t-4.856.409T3.006 19M6.5 14.862q1.375-.143 2.747-.214T12 14.577t2.753.071t2.747.214L14 10.654l-2.677 3.188l-2-2.4z");
}

</style>
