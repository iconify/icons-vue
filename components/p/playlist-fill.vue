<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w65ec5b_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:playlist-fill" /></template>
<style>
.w65ec5b_z {
  fill: currentColor;
  d: path("M3 5h18a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m11 6c0-.239.075-.47.216-.664c.257-.353.685-.508 1.112-.508c.39 0 .771.104 1.119.278l4 2a2.116 2.116 0 0 1 0 3.788l-4 2a2.5 2.5 0 0 1-1.119.278c-.427 0-.855-.155-1.112-.508A1.13 1.13 0 0 1 14 17ZM3 11h8a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m13 4.882l3.553-1.776a.12.12 0 0 0 .065-.106a.12.12 0 0 0-.065-.106L16 12.118ZM3 17h8a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2");
}

</style>
