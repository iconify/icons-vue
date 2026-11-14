<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ztfzicbxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:trunk-open-warning" /></template>
<style>
.ztfzicbxu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 13.5V15q0 2.25 2.25 2.25h.256q-.006.122-.006.25q0 2.75 2.75 2.75t2.75-2.75q0-.128-.006-.25h4.512q-.006.122-.006.25q0 2.75 2.75 2.75t2.75-2.75q0-.128-.006-.25H20q2.25 0 2.25-2.25v-2.5q0-1.947-2.039-2.47l-1.223-.408l-2.087-3.247q-.59-1.125-2.151-1.125h-4.5q-1.575 0-2.161 1.144L6.571 9.052L3.014 5.704q-.109-.102-.248-.155q-.14-.053-.289-.049q-.149.005-.285.066t-.238.17q-.051.054-.09.116t-.065.132t-.039.142t-.01.147t.019.146t.047.139t.073.127q.043.061.097.111L6 10.574v.926H4q-2.25 0-2.25 2m14.014 3.75h2.472q.014.118.014.25q0 1.25-1.25 1.25t-1.25-1.25q0-.132.014-.25M5.75 17.5q0-.132.014-.25h2.472q.014.118.014.25q0 1.25-1.25 1.25T5.75 17.5");
}

</style>
