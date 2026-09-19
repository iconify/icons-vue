<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uw5vu58kl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-equals" /></template>
<style>
.uw5vu58kl {
  fill: currentColor;
  d: path("M19 9.998H5v-2h14zm0 6H5v-2h14z");
}

</style>
