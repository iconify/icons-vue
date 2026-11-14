<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w4huhzcem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:user-shield" /></template>
<style>
.w4huhzcem {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.818 5.068Q4.5 6.386 4.5 8.25t1.318 3.182T9 12.75t3.182-1.318T13.5 8.25t-1.318-3.182T9 3.75T5.818 5.068m12.97.74l3 1.25q.103.042.189.113q.085.071.147.163t.094.199t.032.217v2.75q0 3.415-3.447 4.936q-.145.064-.303.064t-.303-.064Q14.75 13.915 14.75 10.5V7.75q0-.111.032-.217q.032-.107.094-.199t.147-.163t.189-.113l3-1.25q.138-.058.288-.058t.288.058M1.75 20q0-2.427 2.213-4.015Q6.03 14.5 9 14.5t5.037 1.485Q16.25 17.573 16.25 20q0 1.75-1.75 1.75h-11q-1.75 0-1.75-1.75");
}

</style>
