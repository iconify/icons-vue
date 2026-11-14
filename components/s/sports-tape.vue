<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="il_bihbka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:sports-tape" /></template>
<style>
.il_bihbka {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 11.5q0-3.624 2.563-6.187T10.5 2.75t6.187 2.563T19.25 11.5q0 2.348-1.075 4.25H19.5q.093 0 .182.023q.09.022.172.066q.082.043.15.106q.069.062.12.139l2 3q.126.189.126.416q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-11q-3.624 0-6.187-2.563T1.75 11.5m4.5 0q0-1.76 1.245-3.005T10.5 7.25t3.005 1.245T14.75 11.5t-1.245 3.005T10.5 15.75t-3.005-1.245T6.25 11.5m9.174 7.25h4.675l-1-1.5h-2q-.197.222-.412.437q-.602.602-1.263 1.063");
}

</style>
