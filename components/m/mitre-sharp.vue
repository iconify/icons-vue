<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="skdysz1ia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mitre-sharp" /></template>
<style>
.skdysz1ia {
  fill: currentColor;
  d: path("M13.77 14.116V9.885h2.115v-3.77h-2.116v-4.23H19v4.23h-2.116v3.77H19v4.23zm-8.77 8v-4.232h2.116v-3.768H5V9.885h2.116v-3.77H5v-4.23h5.23v4.23H8.117v3.77h2.115v4.23H8.116v3.77h2.115v4.23z");
}

</style>
