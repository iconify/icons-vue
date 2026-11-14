<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i48onibfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:race-car-number" /></template>
<style>
.i48onibfr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 12v3.5q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h1.438q-.188.531-.188 1.25q0 2.75 2.75 2.75t2.75-2.75q0-.719-.188-1.25h5.876q-.188.531-.188 1.25q0 2.75 2.75 2.75t2.75-2.75q0-.719-.188-1.25H21.5q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V12q0-2.105-2.066-2.479l-1.242-.414l-3.363-4.084q-.107-.13-.259-.201T15 4.75h-5q-.09 0-.178.021q-.087.022-.167.063q-.08.042-.148.101t-.12.132L6.568 9.062l-2.691.448Q1.75 9.865 1.75 12M12 7.5q3 0 3 3t-3 3t-3-3t3-3");
}

</style>
