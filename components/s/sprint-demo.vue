<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kcgz7pbwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:sprint-demo" /></template>
<style>
.kcgz7pbwr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18 2.25H6q-1.76 0-3.005 1.245T1.75 6.5V13q0 1.76 1.245 3.005T6 17.25h3.065l-.667 3H7.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141T6.75 21q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h9q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014h-.898l-.667-3H18q1.76 0 3.005-1.245T22.25 13V6.5q0-1.76-1.245-3.005T18 2.25m-3.935 18l-.667-3h-2.796l-.667 3zM12.729 6.885l1.504.981q1.02.666 1.02 1.884t-1.02 1.884l-1.504.981q-1.123.732-2.301.094q-1.177-.638-1.178-1.978V8.769q.001-1.34 1.178-1.978t2.301.094");
}

</style>
