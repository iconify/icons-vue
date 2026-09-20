<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ow1l7hbgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:view-list-outline-sharp" /></template>
<style>
.ow1l7hbgi {
  fill: currentColor;
  d: path("M9 18h11v-2.675H9zM4 8.675h3V6H4zm0 4.675h3v-2.675H4zM4 18h3v-2.675H4zm5-4.65h11v-2.675H9zm0-4.675h11V6H9zM2 20V4h20v16z");
}

</style>
