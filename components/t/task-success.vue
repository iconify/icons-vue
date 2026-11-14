<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uhz6kc1fy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:task-success" /></template>
<style>
.uhz6kc1fy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.688 2.608q-1.688-.974-3.375 0L4.71 5.843q-1.688.974-1.687 2.923v6.468q-.001 1.949 1.687 2.924l5.603 3.234q1.688.974 3.375 0l5.602-3.235q1.688-.974 1.687-2.923V8.766q.001-1.949-1.687-2.924zM10.95 14.389l4.474-5.369q.047-.057.105-.103q.057-.047.122-.081q.066-.034.137-.055t.144-.028t.147.001t.144.03q.071.022.136.057q.064.036.121.083t.103.105t.081.122q.034.066.055.137t.028.144t-.001.147t-.03.144t-.057.136q-.036.064-.083.121l-5 6q-.022.026-.046.05q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094l-3-3q-.106-.105-.163-.243T7.25 12.5t.057-.287t.163-.243q.052-.053.113-.094t.13-.069t.141-.043T8 11.75t.146.014q.073.015.141.043t.13.069t.113.094z");
}

</style>
