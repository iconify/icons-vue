<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="urho3jbau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:table-fill-sharp" /></template>
<style>
.urho3jbau {
  fill: currentColor;
  d: path("M4 3h7v5H3V4a1 1 0 0 1 1-1m9 0h7a1 1 0 0 1 1 1v4h-8ZM3 10h8v4H3Zm18 4h-8v-4h8ZM3 16h8v5H4a1 1 0 0 1-1-1Zm10 5v-5h8v4a1 1 0 0 1-1 1Z");
}

</style>
