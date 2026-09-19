<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cpxd199ve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-reset-tv" /></template>
<style>
.cpxd199ve {
  fill: currentColor;
  d: path("M20 10h-7.01V7L9 11l3.99 4v-3H20v5H4V5h16v3h2V5c0-1.1-.9-2-2-2H4c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h4v2h8v-2h4c1.1 0 1.99-.9 1.99-2v-5H22c0-1.1-.9-2-2-2");
}

</style>
