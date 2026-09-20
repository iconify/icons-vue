<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zise10hoh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:videocam-off" /></template>
<style>
.zise10hoh {
  fill: currentColor;
  d: path("m20.577 15.77l-3.039-3.04v2.118L7.692 5h8.232q.69 0 1.153.463t.463 1.153v4.653l3.038-3.038zm-1.18 5.196L2.418 3.988l.708-.708l16.977 16.977zM4.884 5.037L17.5 17.655q-.096.575-.53.96q-.433.386-1.047.386H5.153q-.69 0-1.152-.462t-.462-1.153V6.615q0-.613.385-1.047t.96-.53");
}

</style>
