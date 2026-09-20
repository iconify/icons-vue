<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k34qr1a1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:split-scene-up-rounded" /></template>
<style>
.k34qr1a1d {
  fill: currentColor;
  d: path("M6.616 20q-.691 0-1.153-.462T5 18.384v-3q0-.213.143-.356q.144-.144.357-.144h13q.214 0 .357.144q.143.143.143.356v3q0 .691-.462 1.153T17.384 20zM3.5 12.5q-.213 0-.357-.143T3 12t.143-.357t.357-.143H5V5.616q0-.691.463-1.153T6.616 4h10.769q.69 0 1.153.463T19 5.616V11.5h1.5q.214 0 .357.143T21 12t-.143.357t-.357.143z");
}

</style>
