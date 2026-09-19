<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wvncf2b8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-table-bar" /></template>
<style>
.wvncf2b8f {
  fill: currentColor;
  d: path("M22 7.5C22 5.57 17.52 4 12 4S2 5.57 2 7.5c0 1.81 3.95 3.31 9 3.48V15H8l-2 5h2l1.2-3h5.6l1.2 3h2l-2-5h-3v-4.02c5.05-.17 9-1.67 9-3.48");
}

</style>
