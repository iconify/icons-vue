<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="krqtpqb7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:speed-2-sharp" /></template>
<style>
.krqtpqb7t {
  fill: currentColor;
  d: path("M13.4 15.425q.65-.65.6-1.5t-.75-1.4q-1.975-1.55-4.1-2.875t-4.175-2.7q1.35 2.075 2.675 4.188t2.8 4.187q.5.725 1.4.738t1.55-.638M3.9 20q-.875-1.575-1.412-2.925t-.513-3.225q0-2 .838-3.787t2.225-3.138t3.187-2.137T12 4q2.075 0 3.888.788t3.174 2.15t2.15 3.175T22 14q0 1.85-.513 3.138T20.1 20z");
}

</style>
