<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sw5csmw_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:shield-keyhole-24-filled" /></template>
<style>
.sw5csmw_n {
  fill: currentColor;
  d: path("M3 5.75V11c0 5.001 2.958 8.676 8.725 10.948a.75.75 0 0 0 .55 0C18.042 19.676 21 16 21 11V5.75a.75.75 0 0 0-.75-.75c-2.663 0-5.258-.943-7.8-2.85a.75.75 0 0 0-.9 0C9.008 4.057 6.413 5 3.75 5a.75.75 0 0 0-.75.75M13.995 11a2 2 0 0 1-1.245 1.852v2.398a.75.75 0 0 1-1.5 0v-2.394A2 2 0 1 1 13.995 11");
}

</style>
