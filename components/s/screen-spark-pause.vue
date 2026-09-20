<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fgqao58ui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:screen-spark-pause" /></template>
<style>
.fgqao58ui {
  fill: currentColor;
  d: path("M15.165 20.893Q14 19.73 14 18.058t1.165-2.836T18 14.058t2.836 1.164T22 18.058q0 1.67-1.164 2.835Q19.67 22.058 18 22.058t-2.835-1.165m1.393-1.143h.769v-3.384h-.77zm2.115 0h.77v-3.384h-.77zM4.616 19q-.691 0-1.154-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h14.77q.69 0 1.152.463T21 6.616v5.428q-.677-.35-1.43-.543T18 11.308q-.598 0-1.178.106q-.58.105-1.122.311q-1.315-.396-2.233-1.364T12.2 8.054q-.05-.15-.2-.15t-.2.15q-.361 1.39-1.359 2.387q-.997.997-2.387 1.359q-.15.03-.15.2q0 .15.15.2q1.319.35 2.278 1.248t1.374 2.194q-.225.562-.34 1.17q-.116.61-.116 1.246q0 .236.017.476q.018.241.072.466z");
}

</style>
