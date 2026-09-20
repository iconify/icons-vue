<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7-t6qz1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:vr180-create2d-sharp" /></template>
<style>
.s7-t6qz1w {
  fill: currentColor;
  d: path("M10 22V10h12v12zm2.5-3h7l-2.3-3l-1.7 2.25l-1.2-1.65zM8 17.75q-2.675-.675-4.337-2.838T2 10q0-3.35 2.325-5.675T10 2q2.75 0 4.913 1.662T17.75 8H8z");
}

</style>
