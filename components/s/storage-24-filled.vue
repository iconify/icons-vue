<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o38j5-27i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:storage-24-filled" /></template>
<style>
.o38j5-27i {
  fill: currentColor;
  d: path("M5 7h14a3 3 0 0 1 2.995 2.824L22 10v4a3 3 0 0 1-2.824 2.995L19 17H5a3 3 0 0 1-2.995-2.824L2 14v-4a3 3 0 0 1 2.824-2.995zh14zm13 3a1 1 0 1 0 0 2a1 1 0 0 0 0-2m-4 0a1 1 0 1 0 0 2a1 1 0 0 0 0-2");
}

</style>
