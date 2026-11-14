<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lo2gtpf0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:voicemail-new" /></template>
<style>
.lo2gtpf0e {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8 2.75H5q-1.139 0-1.945.805q-.805.806-.805 1.945l.001.047q.393 6.283 5.156 11.046t11.046 5.156l.047.001q2.75 0 2.75-2.75v-3q0-.113-.033-.222q-.034-.108-.098-.201t-.153-.164t-.194-.112l-4.5-1.75q-.056-.022-.115-.034t-.119-.016t-.12.003t-.118.023t-.112.041t-.105.059q-.05.033-.094.074t-.081.089l-1.365 1.755q-3.605-1.983-5.588-5.588l1.755-1.365q.048-.037.089-.081t.074-.094t.059-.105t.041-.112t.023-.118t.003-.12t-.016-.119t-.034-.115l-1.75-4.5q-.041-.105-.112-.194q-.07-.089-.164-.153q-.093-.064-.201-.098Q8.113 2.75 8 2.75M15.25 6q0-2.75 2.75-2.75T20.75 6T18 8.75T15.25 6");
}

</style>
