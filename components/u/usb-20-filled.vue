<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="u_yf2vaiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:usb-20-filled" /></template>
<style>
.u_yf2vaiw {
  fill: currentColor;
  d: path("M9.368.851a.75.75 0 0 1 1.272 0l1.249 1.996a.75.75 0 0 1-.636 1.147h-.503v7.327l2.833-2.534A1.25 1.25 0 0 0 14 7.855V7.5h-.25a.75.75 0 0 1-.75-.75v-2a.75.75 0 0 1 .75-.75h2a.75.75 0 0 1 .75.75v2a.75.75 0 0 1-.75.75h-.25v.355a2.75 2.75 0 0 1-.916 2.05l-3.417 3.058a1.25 1.25 0 0 0-.417.932v1.251a2 2 0 1 1-1.691.088a1.3 1.3 0 0 0-.226-.271l-3.417-3.058a2.75 2.75 0 0 1-.916-2.05V9.33A1.748 1.748 0 0 1 5.25 6A1.75 1.75 0 0 1 6 9.33v.526c0 .356.152.695.417.932l2.833 2.534V3.994h-.495a.75.75 0 0 1-.636-1.147z");
}

</style>
