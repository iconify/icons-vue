<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vc8x86bpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mark-email-unread-outline-sharp" /></template>
<style>
.vc8x86bpr {
  fill: currentColor;
  d: path("M3 19V5h11.562q-.043.25-.052.49t.013.51H4.308L12 11l3.573-2.333q.177.171.359.332t.382.297L12 12.116L4 6.885v10.5q0 .269.173.442t.443.173h14.769q.269 0 .442-.173t.173-.443V10.15q.287-.067.527-.158q.24-.09.473-.223V19zM4 6v12zm13.23 1.539q-.73-.731-.73-1.77T17.23 4T19 3.27t1.77.73t.73 1.77t-.73 1.769t-1.77.73t-1.77-.73");
}

</style>
