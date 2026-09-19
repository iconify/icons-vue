<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="msx9kxxqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-chat" /></template>
<style>
.msx9kxxqm {
  fill: currentColor;
  d: path("M22 2H2.01L2 22l4-4h16zM6 9h12v2H6zm8 5H6v-2h8zm4-6H6V6h12z");
}

</style>
