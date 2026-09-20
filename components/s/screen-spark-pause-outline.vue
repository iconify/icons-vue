<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e2b4g5bsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:screen-spark-pause-outline" /></template>
<style>
.e2b4g5bsv {
  fill: currentColor;
  d: path("M4 18V6v5.627v-.32zm7.339 1H4.615q-.69 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h14.77q.69 0 1.152.463T21 6.616v5.428q-.239-.132-.479-.235T20 11.627V6.616q0-.231-.192-.424T19.385 6H4.615q-.23 0-.423.192T4 6.616v10.769q0 .23.192.423t.423.192h6.635q0 .256.017.506t.072.494m3.825 1.893Q14 19.73 14 18.058t1.165-2.836T18 14.058t2.836 1.164T22 18.058q0 1.67-1.164 2.835Q19.67 22.058 18 22.058t-2.835-1.165m1.393-1.143h.769v-3.384h-.77zm2.115 0h.77v-3.384h-.77zm-6.967-4.108q.53-1.375 1.575-2.39t2.419-1.527q-1.244-.373-2.191-1.327T12.2 8.054q-.05-.15-.2-.15t-.2.15q-.361 1.39-1.359 2.387q-.997.997-2.387 1.359q-.15.03-.15.2q0 .15.15.2q1.39.362 2.325 1.299t1.327 2.143");
}

</style>
