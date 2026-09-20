<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mjsrx_zmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:shades-outline-rounded" /></template>
<style>
.mjsrx_zmc {
  fill: currentColor;
  d: path("M4.79 20.98q-.348 0-.569-.201Q4 20.577 4 20.134V4h-.5q-.213 0-.357-.143T3 3.5t.143-.357T3.5 3h17q.214 0 .357.143T21 3.5t-.143.357T20.5 4H20v16.135q-.025.442-.246.644t-.57.202q-1.694 0-3.1-1.468q-1.405-1.467-1.694-3.013H9.585q-.289 1.546-1.695 3.014q-1.405 1.467-3.1 1.467M5 19.908q1.58-.35 2.656-1.562Q8.73 17.135 8.73 15.5V4H5zM9.73 15.5h4.54V4H9.73zM19 19.889V4h-3.73v11.5q0 1.616 1.059 2.83q1.06 1.214 2.671 1.559M8.73 4H5zM19 4h-3.73z");
}

</style>
