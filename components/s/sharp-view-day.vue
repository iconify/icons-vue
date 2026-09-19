<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t3rq_2x_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-view-day" /></template>
<style>
.t3rq_2x_q {
  fill: currentColor;
  d: path("M2 21h19v-3H2zM21 8H2v8h19zM2 3v3h19V3z");
}

</style>
