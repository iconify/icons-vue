<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lpx_ecb8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:workforce-planning" /></template>
<style>
.lpx_ecb8p {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 5q0-2.75 2.75-2.75T7.75 5T5 7.75T2.25 5M12 2.25Q9.25 2.25 9.25 5T12 7.75T14.75 5T12 2.25M16.25 5q0-2.75 2.75-2.75T21.75 5T19 7.75T16.25 5M7.375 8.75h-1.25Q4 8.75 4 10.875q0 .772.28 1.263q-.568.329-1.066.826Q1.75 14.429 1.75 16.5t1.464 3.536Q4.679 21.5 6.75 21.5t3.536-1.464q1.464-1.465 1.464-3.536q0-.655-.147-1.25h.794q-.147.595-.147 1.25q0 2.071 1.464 3.536Q15.179 21.5 17.25 21.5t3.536-1.464q1.464-1.465 1.464-3.536t-1.464-3.536q-.498-.497-1.066-.826q.28-.491.28-1.263q0-2.125-2.125-2.125h-1.25q-2.125 0-2.125 2.125q0 .772.28 1.263q-.568.329-1.066.826q-.374.375-.652.789q-.031-.003-.062-.003h-2q-.031 0-.062.003q-.278-.414-.652-.789q-.498-.497-1.066-.826q.28-.491.28-1.263q0-2.125-2.125-2.125");
}

</style>
