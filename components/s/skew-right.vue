<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b16f1196j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:skew-right" /></template>
<style>
.b16f1196j {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M21.5 21.25q-6.008 0-9.196-7.971l-.009-.023Q9.747 6.25 7 6.25q-.882 0-2.707 9.295q-.683 3.482-1.062 5.124q-.017.072-.047.139t-.073.127q-.043.061-.097.111t-.117.09t-.131.065q-.069.027-.142.039t-.147.01q-.074-.003-.146-.019q-.145-.034-.266-.12q-.122-.087-.201-.214q-.079-.126-.104-.273t.009-.293q.373-1.617 1.052-5.075Q4.884 4.75 7 4.75q3.795 0 6.701 7.982q2.811 7.018 7.799 7.018q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014");
}

</style>
