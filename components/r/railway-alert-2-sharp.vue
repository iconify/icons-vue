<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fdpc7_g7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:railway-alert-2-sharp" /></template>
<style>
.fdpc7_g7r {
  fill: currentColor;
  d: path("m3 21l1.539-1.538h10.923L17 21zm7.928-6.034q.38-.38.38-.928t-.38-.928t-.928-.38t-.928.38t-.38.928t.38.928t.928.38t.928-.38M16.616 11q-1.672 0-2.836-1.164Q12.616 8.67 12.616 7q0-1.666 1.161-2.833T16.616 3q1.67 0 2.835 1.165Q20.616 5.329 20.616 7T19.44 9.836T16.616 11m-.385-3.384H17v-3h-.77zm.384 1.846q.2 0 .322-.131q.12-.131.14-.312q0-.2-.13-.34q-.131-.14-.331-.14t-.331.13t-.131.331t.13.33q.132.132.332.132m-11.308 9.23l.769-.769h-.25q-1.2 0-2.013-.842T3 15.038V8.192q0-2.84 2.024-4.516T10 2q.61 0 1.201.068t1.126.23q-.787.71-1.307 1.657T10.32 6H4.482q-.239.489-.361 1.034T4 8.192v1.962h7.127q.784 1.45 2.247 2.34t3.247.89q.096 0 .19-.002q.093-.003.189-.015v1.672q0 1.2-.813 2.042t-2.014.842h-.25l.77.77z");
}

</style>
