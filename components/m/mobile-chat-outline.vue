<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f4_bjfzsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-chat-outline" /></template>
<style>
.f4_bjfzsg {
  fill: currentColor;
  d: path("M7 21V3zm10 0v-2.308zm-2.884-5.692h5.653v-4h-5.653zm-1 2.48v-6.672q0-.349.23-.578t.577-.23h6.039q.348 0 .578.23t.23.578V15.5q0 .348-.23.578t-.578.23h-5.366zM7.616 22q-.672 0-1.144-.472T6 20.385V3.615q0-.67.472-1.143Q6.944 2 7.616 2h8.769q.67 0 1.143.472q.472.472.472 1.144v4.307h-1V3.616q0-.27-.173-.443T16.385 3h-8.77q-.269 0-.442.173T7 3.616v16.769q0 .269.173.442t.443.173h8.769q.269 0 .442-.173t.173-.442v-1.693h1v1.693q0 .67-.472 1.143q-.472.472-1.143.472zm4.972-15.912q.22-.22.22-.55q0-.329-.22-.549t-.55-.22t-.548.22t-.22.55t.22.549t.549.22t.549-.22m1.528 9.22v-4z");
}

</style>
