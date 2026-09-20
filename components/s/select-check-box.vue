<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qo8b2kb0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:select-check-box" /></template>
<style>
.qo8b2kb0o {
  fill: currentColor;
  d: path("M5.616 20q-.672 0-1.144-.472T4 18.385V5.615q0-.67.472-1.143Q4.944 4 5.616 4h12.769q.257 0 .49.076t.427.228l-.83.83q-.058-.057-.145-.096T18.125 5H5.615q-.269 0-.442.173T5 5.616v12.769q0 .269.173.442t.443.173h12.769q.269 0 .442-.173t.173-.443V11.64l1-1v7.746q0 .67-.472 1.143q-.472.472-1.143.472zm5.909-3.712l-4.554-4.553l.708-.708l3.865 3.865l8.79-8.79l.695.683z");
}

</style>
