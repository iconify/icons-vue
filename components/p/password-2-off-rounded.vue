<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hut_02afo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:password-2-off-rounded" /></template>
<style>
.hut_02afo {
  fill: currentColor;
  d: path("M4.405 12.635q-1.001 0-1.703-.705T2 10.218t.7-1.699t1.703-.692q1 0 1.703.696t.702 1.689q0 1.01-.701 1.716q-.701.707-1.702.707m13.49-.72q-.703-.701-.703-1.702t.701-1.703t1.702-.702t1.703.7t.702 1.703q0 1-.7 1.703t-1.703.702q-1 0-1.703-.701m-3.49-1.703q0 .103-.015.206l-.033.213q-.062.236-.297.309q-.236.072-.447-.14L11.43 8.58q-.187-.186-.127-.421q.06-.236.296-.303q.09-.018.2-.033t.2-.015q1.002 0 1.703.7q.7.702.7 1.704M3.617 18.23q-.262 0-.439-.182T3 17.616t.177-.434t.439-.182h11.969L2.446 3.862q-.14-.14-.15-.345t.15-.363t.354-.16t.354.16l17.692 17.692q.14.14.15.345q.01.203-.15.363t-.354.16t-.353-.16l-3.323-3.323z");
}

</style>
