<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t_2ihygiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-signal-cellular-connected-no-internet-0-bar" /></template>
<style>
.t_2ihygiv {
  fill: currentColor;
  d: path("M21 18c.55 0 1-.45 1-1v-6c0-.55-.45-1-1-1s-1 .45-1 1v6c0 .55.45 1 1 1m0 4c.55 0 1-.45 1-1s-.45-1-1-1s-1 .45-1 1s.45 1 1 1m-3-2v2H2L22 2v6h-2V6.83L6.83 20z");
}

</style>
