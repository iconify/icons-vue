<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y4aqv-bed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:signal-cellular-pause-outline-rounded" /></template>
<style>
.y4aqv-bed {
  fill: currentColor;
  d: path("M4.373 19.627L19.627 4.373q.379-.379.876-.171t.497.742v8.287q0 .212-.144.356t-.357.144t-.356-.144t-.143-.356V5.42L5.421 20h8.194q.213 0 .357.144t.144.357t-.144.356t-.357.143h-8.67q-.535 0-.743-.497t.171-.876m12.27 1.23q-.143-.144-.143-.357v-3.884q0-.213.144-.357t.357-.143t.356.143t.143.357V20.5q0 .213-.144.356t-.357.144t-.356-.144m3 0q-.143-.143-.143-.356v-3.884q0-.213.144-.357t.357-.143t.356.143t.143.357V20.5q0 .213-.144.356t-.357.144t-.356-.144m-6.93-8.148");
}

</style>
