<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a667o9btw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:password-2-off-outline" /></template>
<style>
.a667o9btw {
  fill: currentColor;
  d: path("M4.405 12.635q-1.001 0-1.703-.705T2 10.218t.7-1.699t1.703-.692q1 0 1.703.696t.702 1.689q0 1.01-.701 1.716q-.701.707-1.702.707m13.49-.72q-.703-.701-.703-1.702t.701-1.703t1.702-.702t1.703.7t.702 1.703q0 1-.7 1.703t-1.703.702q-1 0-1.703-.701m-3.76-.592l-3.207-3.246q.228-.135.504-.202T12 7.808q1.002 0 1.703.7q.7.702.7 1.704q0 .303-.066.589t-.202.522m6.357 10.585l-3.677-3.677H3V17h12.585L2.092 3.508L2.8 2.8l18.4 18.4z");
}

</style>
