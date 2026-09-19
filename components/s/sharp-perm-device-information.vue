<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vz2xvyb4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-perm-device-information" /></template>
<style>
.vz2xvyb4k {
  fill: currentColor;
  d: path("M13 7h-2v2h2zm0 4h-2v6h2zM5 1v22h14V1zm12 18H7V5h10z");
}

</style>
