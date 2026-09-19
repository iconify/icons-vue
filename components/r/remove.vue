<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kadpm5bkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:remove" /></template>
<style>
.kadpm5bkp {
  fill: currentColor;
  d: path("M19 13H5v-2h14z");
}

</style>
