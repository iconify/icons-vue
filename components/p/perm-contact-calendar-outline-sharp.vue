<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="utdsz_hxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:perm-contact-calendar-outline-sharp" /></template>
<style>
.utdsz_hxc {
  fill: currentColor;
  d: path("M12 17.27q-1.708 0-3.31.629q-1.601.63-2.978 1.928V20H18.23v-.173q-1.339-1.298-2.922-1.928q-1.582-.63-3.309-.63m-7 1.85q1.35-1.325 3.138-2.087T12 16.269t3.863.763T19 19.119V6H5zm4.871-6.49Q9 11.758 9 10.5t.871-2.129T12 7.5t2.129.871T15 10.5t-.871 2.129T12 13.5t-2.129-.871m3.538-.72Q14 11.317 14 10.5t-.591-1.409Q12.817 8.5 12 8.5t-1.409.591Q10 9.683 10 10.5t.591 1.409q.592.591 1.409.591t1.409-.591M4 21V5h3.385V2.77h1.077V5h7.154V2.77h1V5H20v16zm8-1h6.23H5.713z");
}

</style>
