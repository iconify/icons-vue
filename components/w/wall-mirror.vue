<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ievig8bxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:wall-mirror" /></template>
<style>
.ievig8bxr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.446 4.838Q4.25 7.818 4.25 12t2.196 7.162Q8.722 22.25 12 22.25t5.554-3.088Q19.75 16.182 19.75 12t-2.196-7.162Q15.278 1.75 12 1.75T6.446 4.838M11.97 6.47q.105-.106.243-.163t.287-.057t.287.057t.243.163q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113l-4 4q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.106-.105-.163-.243T7.75 11t.057-.287t.163-.243z");
}

</style>
