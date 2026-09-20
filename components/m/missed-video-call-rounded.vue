<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="abcxx_6us"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:missed-video-call-rounded" /></template>
<style>
.abcxx_6us {
  fill: currentColor;
  d: path("M11.517 14.904q.137-.056.268-.187l2.888-2.913q.14-.14.153-.342t-.153-.366q-.16-.16-.354-.16t-.353.16l-2.747 2.785l-3.43-3.42h1.769q.213 0 .357-.143t.143-.356t-.143-.357t-.357-.143H6.866q-.349 0-.578.23q-.23.23-.23.577v2.692q0 .214.143.357t.357.143t.357-.143t.143-.357v-1.815l3.596 3.596q.13.131.267.174t.298.043t.298-.055M5.097 19q-.691 0-1.154-.462t-.462-1.153V6.615q0-.69.462-1.152T5.096 5h10.77q.69 0 1.152.463t.463 1.153v4.653l2.342-2.342q.192-.192.444-.096t.252.369v5.6q0 .273-.252.37q-.252.095-.444-.097l-2.342-2.342v4.654q0 .69-.463 1.153T15.866 19z");
}

</style>
