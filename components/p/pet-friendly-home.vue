<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o7wp58xaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pet-friendly-home" /></template>
<style>
.o7wp58xaz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.935 9.143L9.81 4.132q2.19-1.866 4.38 0l5.875 5.011q1.185 1.011 1.185 2.568v1.795q-.122-.006-.25-.006q-.225 0-.432.018Q20.043 12 18 12t-2.568 1.518Q15.225 13.5 15 13.5q-2.75 0-2.75 2.75q0 1.796 1.173 2.419q-.173.505-.173 1.081q0 .824.354 1.5H6.125q-3.375 0-3.375-3.375v-6.164q0-1.557 1.185-2.568M18 13.25q-1.5 0-1.5 1.5t1.5 1.5t1.5-1.5t-1.5-1.5m-4.5 3q0-1.5 1.5-1.5t1.5 1.5t-1.5 1.5t-1.5-1.5m6 0q0-1.5 1.5-1.5t1.5 1.5t-1.5 1.5t-1.5-1.5m-1.5 1q-3.5 0-3.5 2.5t3.5 2.5q1.357 0 2.347-.63q1.153-.733 1.153-1.87t-1.153-1.87q-.99-.63-2.347-.63m0 1.5q.921 0 1.542.395q.458.292.458.605t-.458.605q-.621.395-1.542.395q-2 0-2-1t2-1");
}

</style>
