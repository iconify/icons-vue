<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uvwn2ebvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:width-full-rounded" /></template>
<style>
.uvwn2ebvq {
  fill: currentColor;
  d: path("M4.616 19q-.672 0-1.144-.472T3 17.385V6.615q0-.67.472-1.143Q3.944 5 4.616 5h14.769q.67 0 1.143.472q.472.472.472 1.144v10.769q0 .67-.472 1.143q-.472.472-1.143.472zm0-1h.807V6h-.807q-.27 0-.443.173T4 6.616v10.769q0 .269.173.442t.443.173m13.961 0h.808q.269 0 .442-.173t.173-.443V6.616q0-.27-.173-.443T19.385 6h-.808z");
}

</style>
