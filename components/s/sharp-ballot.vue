<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j5_sclbbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-ballot" /></template>
<style>
.j5_sclbbi {
  fill: currentColor;
  d: path("M13 9.5h5v-2h-5zm0 7h5v-2h-5zm8 4.5H3V3h18zM6 11h5V6H6zm1-4h3v3H7zM6 18h5v-5H6zm1-4h3v3H7z");
}

</style>
