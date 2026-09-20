<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c1aqs0blr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:spacebar-24-regular" /></template>
<style>
.c1aqs0blr {
  fill: currentColor;
  d: path("M20.5 11v2a.25.25 0 0 1-.25.25H3.75A.25.25 0 0 1 3.5 13v-2A.75.75 0 0 0 2 11v2c0 .966.784 1.75 1.75 1.75h16.5A1.75 1.75 0 0 0 22 13v-2a.75.75 0 0 0-1.5 0");
}

</style>
