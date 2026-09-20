<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tlndzodql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:nutrition" /></template>
<style>
.tlndzodql {
  fill: currentColor;
  d: path("M7.749 18.251Q6 16.502 6 14q0-2.061 1.243-3.674t3.243-2.128q-.709-.142-1.264-.549t-.91-1.016t-.535-1.316t-.156-1.465q.852-.029 1.623.23q.771.26 1.387.772q.615.511 1.006 1.19q.392.679.453 1.52q.306-.737.74-1.396q.433-.659 1.008-1.234q.14-.14.354-.14t.354.14t.14.354t-.14.354q-.53.531-.937 1.145q-.405.615-.663 1.307q2.2.335 3.627 2.009T18 14q0 2.502-1.749 4.251T12 20t-4.251-1.749");
}

</style>
