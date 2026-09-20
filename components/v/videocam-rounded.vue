<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f64q9cbsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:videocam-rounded" /></template>
<style>
.f64q9cbsx {
  fill: currentColor;
  d: path("M5.096 19q-.69 0-1.153-.462t-.462-1.153V6.615q0-.69.462-1.152T5.096 5h10.77q.69 0 1.152.463t.463 1.153v4.653l2.342-2.342q.192-.192.444-.096t.252.369v5.6q0 .273-.252.37q-.252.095-.444-.097l-2.342-2.342v4.654q0 .69-.463 1.153T15.866 19z");
}

</style>
