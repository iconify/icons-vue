<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jrshe9b-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-tab-unselected" /></template>
<style>
.jrshe9b-n {
  fill: currentColor;
  d: path("M1 9h2V7H1zm0 4h2v-2H1zm8 8h2v-2H9zm-8-4h2v-2H1zm0 4h2v-2H1zM23 3H13v6h10zm-2 14h2v-2h-2zM9 5h2V3H9zM5 21h2v-2H5zM5 5h2V3H5zM1 5h2V3H1zm20 8h2v-2h-2zm-8 8h2v-2h-2zm4 0h2v-2h-2zm4 0h2v-2h-2z");
}

</style>
