<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ng_qewbgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:manager-feedback" /></template>
<style>
.ng_qewbgu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.25 5q0-3.25 3.25-3.25h11q3.25 0 3.25 3.25v9.5q0 3.25-3.25 3.25h-2.614l-2.276 3.186q-.043.06-.096.111q-.054.05-.117.089t-.132.066q-.069.026-.142.038t-.146.01q-.074-.003-.146-.019q-.072-.017-.139-.047q-.068-.031-.128-.074q-.102-.072-.174-.174L9.114 17.75H6.5q-3.25 0-3.25-3.25zm8.969-.5h-.438q-.759 0-1.226.598t-.283 1.334l.068.272q.081.323.225.565q-.129.249-.192.578l-.711 3.732q-.223 1.17.619 2.012l.313.314q.583.583 1.406.583t1.405-.583l.315-.314q.841-.842.618-2.011l-.711-3.733q-.063-.329-.192-.578q.144-.242.225-.565l.068-.272q.183-.736-.283-1.334q-.467-.598-1.226-.598");
}

</style>
