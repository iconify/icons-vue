<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":222};
const content = `<path class="gzzr1mstp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:vercel-icon" /></template>
<style>
.gzzr1mstp {
  d: path("m128 0l128 221.705H0z");
}

</style>
