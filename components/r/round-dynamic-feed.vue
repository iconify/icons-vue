<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c1w_sfwjd"/><path class="ld6wv7blk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-dynamic-feed" /></template>
<style>
.c1w_sfwjd {
  fill: currentColor;
  d: path("M7 8c-.55 0-1 .45-1 1v6c0 1.1.9 2 2 2h8c.55 0 1-.45 1-1s-.45-1-1-1H8V9c0-.55-.45-1-1-1");
}

.ld6wv7blk {
  fill: currentColor;
  d: path("M20 3h-8c-1.1 0-2 .9-2 2v6c0 1.1.9 2 2 2h8c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2m0 8h-8V7h8zM3 12c-.55 0-1 .45-1 1v6c0 1.1.9 2 2 2h8c.55 0 1-.45 1-1s-.45-1-1-1H4v-6c0-.55-.45-1-1-1");
}

</style>
