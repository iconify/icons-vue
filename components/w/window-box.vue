<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="im5mopb8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:window-box" /></template>
<style>
.im5mopb8a {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.5 3.25q-3.25 0-3.25 3.25q0 2.85 2.5 3.201v3.049H3.5q-.079 0-.157.017q-.146.031-.269.116q-.123.084-.204.21q-.081.125-.108.272q-.027.146.005.292l1.5 7q.013.063.037.122t.057.114q.033.054.076.102t.091.088q.05.04.106.072t.116.052q.06.021.123.032T5 21.25h14q.064 0 .127-.011t.123-.032t.116-.052q.056-.032.106-.072t.091-.088q.043-.048.076-.102q.033-.055.057-.114t.037-.122l1.5-7q.017-.078.017-.157q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014h-3.25V9.701q2.5-.351 2.5-3.201q0-3.25-3.25-3.25T13.25 6.5q0 2.85 2.5 3.201v3.049h-7.5V9.701q2.5-.351 2.5-3.201q0-3.25-3.25-3.25");
}

</style>
