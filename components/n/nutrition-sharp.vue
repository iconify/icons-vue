<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="neanofh3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:nutrition-sharp" /></template>
<style>
.neanofh3w {
  fill: currentColor;
  d: path("M7.749 18.251Q6 16.502 6 14q0-2.061 1.243-3.674t3.243-2.128q-.709-.142-1.264-.549t-.91-1.016t-.535-1.316t-.156-1.465q.852-.029 1.623.23q.771.26 1.387.772q.615.511 1.006 1.19q.392.679.453 1.52q.306-.737.786-1.442t1.316-1.541l.708.707q-.806.806-1.251 1.46t-.703 1.346q2.2.335 3.627 2.009T18 14q0 2.502-1.749 4.251T12 20t-4.251-1.749");
}

</style>
