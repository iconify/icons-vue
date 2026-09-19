<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lh7khgqsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-markunread-mailbox" /></template>
<style>
.lh7khgqsm {
  fill: currentColor;
  d: path("M20 6H10v5c0 .55-.45 1-1 1s-1-.45-1-1V4h5c.55 0 1-.45 1-1V1c0-.55-.45-1-1-1H7c-.55 0-1 .45-1 1v5H4c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V8c0-1.1-.9-2-2-2");
}

</style>
