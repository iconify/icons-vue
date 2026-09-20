<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x_dsxvbor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:stockpot-rounded" /></template>
<style>
.x_dsxvbor {
  fill: currentColor;
  d: path("M6.423 19q-1.01 0-1.716-.707T4 16.577V8.481q0-.213.144-.356T4.5 7.98h15q.213 0 .356.144T20 8.48v8.096q0 1.01-.707 1.716T17.577 19zM9.5 5.596v-.769q0-.351.23-.59T10.317 4h3.366q.358 0 .587.238t.23.589v.77h5q.213 0 .356.143q.144.144.144.357t-.144.356t-.356.143h-15q-.213 0-.356-.144T4 6.096t.144-.356t.356-.144z");
}

</style>
