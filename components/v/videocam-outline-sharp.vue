<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z98a34bie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:videocam-outline-sharp" /></template>
<style>
.z98a34bie {
  fill: currentColor;
  d: path("M2 20V4h16v6.5l4-4v11l-4-4V20zm2-2h12V6H4zm0 0V6z");
}

</style>
