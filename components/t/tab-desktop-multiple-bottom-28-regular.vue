<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="ftvqt_aci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:tab-desktop-multiple-bottom-28-regular" /></template>
<style>
.ftvqt_aci {
  fill: currentColor;
  d: path("M17.25 7A3.75 3.75 0 0 1 21 10.75v11.5A3.75 3.75 0 0 1 17.25 26H5.75A3.75 3.75 0 0 1 2 22.25v-11.5A3.75 3.75 0 0 1 5.75 7zM5.75 8.5a2.25 2.25 0 0 0-2.25 2.25v8.75h7.25a2.75 2.75 0 0 1 2.75 2.75v2.25h3.75a2.25 2.25 0 0 0 2.25-2.25v-11.5a2.25 2.25 0 0 0-2.25-2.25zM3.5 22.25a2.25 2.25 0 0 0 2.25 2.25H12v-2.25c0-.69-.56-1.25-1.25-1.25H3.5zM20.25 2A5.75 5.75 0 0 1 26 7.75v9.5A3.75 3.75 0 0 1 22.25 21H22v-1.5h.25a2.25 2.25 0 0 0 2.25-2.25v-9.5a4.25 4.25 0 0 0-4.25-4.25h-9.5A2.25 2.25 0 0 0 8.5 5.75V6H7v-.25A3.75 3.75 0 0 1 10.75 2z");
}

</style>
