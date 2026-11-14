<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zwesr-lyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pet-anxiety" /></template>
<style>
.zwesr-lyx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 4.75q0-2.5 2.25-2.5t2.25 2.5t-2.25 2.5T5 4.75m7-2.5q-2.25 0-2.25 2.5T12 7.25t2.25-2.5T12 2.25M2.12 7.524q-.62.724-.62 1.726q0 2.5 2.25 2.5T6 9.25t-2.25-2.5q-.966 0-1.63.774M13.25 9.25q0-2.5 2.25-2.5t2.25 2.5t-2.25 2.5t-2.25-2.5m-8.75 5.5q0-1.804 1.518-3.054Q7.471 10.5 9.5 10.5t3.482 1.196q1.518 1.25 1.518 3.054q0 .126-.007.25q-.988 1.477-1.322 2.641q-.091.082-.189.163Q11.529 19 9.5 19t-3.482-1.196Q4.5 16.554 4.5 14.75m14.064-1.494q3.186 3.641 3.186 5.494q0 3.75-3.75 3.75t-3.75-3.75q0-1.853 3.186-5.494q.098-.112.232-.178q.133-.066.282-.076t.29.038q.142.047.254.146q.038.032.07.07M15.75 18.75q0-1.153 2.25-3.847q2.25 2.694 2.25 3.847Q20.25 21 18 21t-2.25-2.25");
}

</style>
