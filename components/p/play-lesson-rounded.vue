<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vi18c_edl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:play-lesson-rounded" /></template>
<style>
.vi18c_edl {
  fill: currentColor;
  d: path("m9.5 9l1.385.839q.211.13.413.012t.202-.36V4.807q0-.348-.23-.578T10.692 4H8.308q-.348 0-.578.23t-.23.578V9.49q0 .242.202.36t.414-.012zm5.165 11.528Q13.5 19.364 13.5 17.692q0-1.67 1.174-2.835t2.922-1.165q1.594 0 2.75 1.165t1.154 2.835q0 1.672-1.164 2.836q-1.165 1.164-2.836 1.164t-2.835-1.164m2.61-1.407l1.627-1.138q.173-.131.173-.33q0-.197-.173-.328l-1.627-1.138q-.211-.131-.426-.022q-.214.108-.214.35v2.277q0 .243.214.351t.426-.022M5.615 21q-.67 0-1.143-.472Q4 20.056 4 19.385V4.615q0-.67.472-1.143Q4.944 3 5.616 3h10.769q.67 0 1.143.472q.472.472.472 1.144v6.537q0 .241-.164.403q-.165.162-.407.182q-1.192.051-2.223.445t-1.906 1.27q-.835.817-1.317 1.898q-.483 1.08-.483 2.339q0 .61.115 1.198q.114.588.35 1.143q.143.348-.034.659q-.177.31-.531.31z");
}

</style>
