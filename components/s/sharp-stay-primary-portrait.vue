<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bi7egzbxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-stay-primary-portrait" /></template>
<style>
.bi7egzbxv {
  fill: currentColor;
  d: path("M5.01 1v22H19V1zM17 19H7V5h10z");
}

</style>
