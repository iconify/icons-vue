<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q0ctq_pqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-call-received" /></template>
<style>
.q0ctq_pqu {
  fill: currentColor;
  d: path("M15 17H8.41L20 5.41L18.59 4L7 15.59V9H5v10h10z");
}

</style>
