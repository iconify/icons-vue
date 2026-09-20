<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vhx92rfqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:shield-error-24-filled" /></template>
<style>
.vhx92rfqz {
  fill: currentColor;
  d: path("M20.25 5c-2.663 0-5.258-.943-7.8-2.85a.75.75 0 0 0-.9 0C9.008 4.057 6.413 5 3.75 5a.75.75 0 0 0-.75.75V11c0 5.001 2.958 8.676 8.725 10.948a.75.75 0 0 0 .55 0C18.042 19.676 21 16 21 11V5.75a.75.75 0 0 0-.75-.75m-8.993 2.63a.75.75 0 0 1 1.486 0l.007.102v6.5l-.007.102a.75.75 0 0 1-1.486 0l-.007-.102v-6.5zM12 18a1 1 0 1 1 0-2a1 1 0 0 1 0 2");
}

</style>
