<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fl8nzpb_a"/><path class="e_zmqdb1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-contact-page" /></template>
<style>
.e_zmqdb1d {
  fill: currentColor;
  d: path("M13.17 4L18 8.83V20H6V4zM14 2H6c-1.1 0-2 .9-2 2v16c0 1.1.9 2 2 2h12c1.1 0 2-.9 2-2V8zm-2 12c1.1 0 2-.9 2-2s-.9-2-2-2s-2 .9-2 2s.9 2 2 2m4 3.43c0-.81-.48-1.53-1.22-1.85a6.95 6.95 0 0 0-5.56 0A2.01 2.01 0 0 0 8 17.43V18h8z");
}

.fl8nzpb_a {
  fill: currentColor;
  d: path("M13.17 4L18 8.83V20H6V4zM12 14c1.1 0 2-.9 2-2s-.9-2-2-2s-2 .9-2 2s.9 2 2 2m4 3.43c0-.81-.48-1.53-1.22-1.85a6.95 6.95 0 0 0-5.56 0A2.01 2.01 0 0 0 8 17.43V18h8z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
