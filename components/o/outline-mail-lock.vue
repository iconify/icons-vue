<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qzougg38r"/><path class="ckasmk93q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-mail-lock" /></template>
<style>
.ckasmk93q {
  fill: currentColor;
  d: path("M23 15v-1c0-1.1-.9-2-2-2s-2 .9-2 2v1c-.55 0-1 .45-1 1v3c0 .55.45 1 1 1h4c.55 0 1-.45 1-1v-3c0-.55-.45-1-1-1m-3 0v-1c0-.55.45-1 1-1s1 .45 1 1v1z");
}

.qzougg38r {
  fill: currentColor;
  d: path("m4 8l8 5l8-5v2h2V6c0-1.1-.9-2-2-2H4c-1.1 0-1.99.9-1.99 2L2 18c0 1.1.9 2 2 2h12v-2H4zm16-2l-8 5l-8-5z");
}

</style>
