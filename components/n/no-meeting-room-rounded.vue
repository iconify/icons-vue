<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kh_8xrb_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:no-meeting-room-rounded" /></template>
<style>
.kh_8xrb_a {
  fill: currentColor;
  d: path("m17 14.189l-1-1V6h-2v5.189L6.85 4h6.342q.343 0 .544.247q.2.247.264.56V5h2.192q.349 0 .578.23t.23.578zm2.139 6.365L14 15.416v3.776q0 .349-.23.578t-.578.23H4.5q-.213 0-.357-.143T4 19.5t.143-.357T4.5 19H6V7.416L3.446 4.862q-.14-.14-.15-.345q-.01-.203.15-.363t.354-.16t.354.16l15.692 15.692q.14.14.15.345q.01.203-.15.363t-.354.16t-.353-.16");
}

</style>
