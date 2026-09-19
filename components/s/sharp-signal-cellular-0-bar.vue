<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nqaqhdbvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-signal-cellular-0-bar" /></template>
<style>
.nqaqhdbvw {
  fill: currentColor;
  d: path("M2 22h20V2zm18-2H6.83L20 6.83z");
}

</style>
