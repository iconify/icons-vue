<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="q1zixjb0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:speaker-hifi-bold" /></template>
<style>
.q1zixjb0c {
  fill: currentColor;
  d: path("M192 20H64a20 20 0 0 0-20 20v176a20 20 0 0 0 20 20h128a20 20 0 0 0 20-20V40a20 20 0 0 0-20-20m-4 192H68V44h120ZM112 76a16 16 0 1 1 16 16a16 16 0 0 1-16-16m16 120a44 44 0 1 0-44-44a44.05 44.05 0 0 0 44 44m0-64a20 20 0 1 1-20 20a20 20 0 0 1 20-20");
}

</style>
