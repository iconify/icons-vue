<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mdwr8wbtk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:turn-left-outline-sharp" /></template>
<style>
.mdwr8wbtk {
  fill: currentColor;
  d: path("M15 20v-9H6.8l1.6 1.6L7 14l-4-4l4-4l1.4 1.4L6.8 9H17v11z");
}

</style>
