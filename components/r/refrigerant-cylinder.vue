<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z1g-hpo2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:refrigerant-cylinder" /></template>
<style>
.z1g-hpo2v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.5 20.393V21.5h-10V11q0-.123.006-.245q.006-.123.018-.245t.03-.244t.042-.241q.024-.121.054-.24t.065-.236t.077-.233t.089-.229t.099-.225q.053-.111.11-.219q.058-.108.121-.214q.063-.105.132-.207q.068-.102.141-.2t.151-.194q.078-.095.16-.186q.083-.091.169-.178q.087-.086.178-.169q.091-.082.186-.16t.194-.151q.098-.073.2-.141q.102-.069.207-.132q.106-.063.214-.121t.219-.11t.225-.099t.229-.089t.233-.077t.236-.065t.24-.054q.12-.024.241-.042q.122-.018.244-.03t.245-.018T8.5 6t.245.006t.245.018t.244.03t.241.042q.121.024.24.054t.236.065t.233.077t.229.089q.114.047.225.099t.219.11t.214.121t.207.132t.2.141t.194.151t.186.16q.091.083.178.169q.086.087.169.178q.082.091.16.186t.151.194t.141.2q.069.102.132.207q.063.106.121.214t.11.219t.099.225q.047.113.089.229q.041.115.077.233q.035.117.065.236t.054.24q.024.12.042.241q.018.122.03.244t.018.245t.006.245v5.593M8.5 2.5V6M6 2.5h5m8 13v6M16.5 17l5 3m-5 0l5-3");
}

</style>
