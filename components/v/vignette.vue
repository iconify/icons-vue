<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="optm-2b8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:vignette" /></template>
<style>
.optm-2b8z {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18 3.75H6q-1.76 0-3.005 1.245T1.75 8v8q0 1.76 1.245 3.005T6 20.25h12q1.76 0 3.005-1.245T22.25 16V8q0-1.76-1.245-3.005T18 3.75M4.75 12q0-2.257 2.227-3.799Q9.073 6.75 12 6.75t5.023 1.451Q19.25 9.743 19.25 12t-2.227 3.799Q14.927 17.25 12 17.25t-5.023-1.451Q4.75 14.257 4.75 12");
}

</style>
