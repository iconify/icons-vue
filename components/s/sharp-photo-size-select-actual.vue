<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d0zzatbid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-photo-size-select-actual" /></template>
<style>
.d0zzatbid {
  fill: currentColor;
  d: path("M23 3H1v18h22zM5 17l3.5-4.5l2.5 3.01L14.5 11l4.5 6z");
}

</style>
