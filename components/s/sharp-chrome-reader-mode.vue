<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h0w4lmbal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-chrome-reader-mode" /></template>
<style>
.h0w4lmbal {
  fill: currentColor;
  d: path("M13 12h7v1.5h-7zm0-2.5h7V11h-7zm0 5h7V16h-7zM23 4H1v17h22zm-2 15h-9V6h9z");
}

</style>
