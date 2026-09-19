<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-id84bjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-card-membership" /></template>
<style>
.i-id84bjr {
  fill: currentColor;
  d: path("M22 2H2v15h6v5l4-2l4 2v-5h6zm-2 13H4v-2h16zm0-5H4V4h16z");
}

</style>
