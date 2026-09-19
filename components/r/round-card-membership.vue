<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jc1vp68up"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-card-membership" /></template>
<style>
.jc1vp68up {
  fill: currentColor;
  d: path("M20 2H4c-1.11 0-2 .89-2 2v11c0 1.11.89 2 2 2h4v5l4-2l4 2v-5h4c1.11 0 2-.89 2-2V4c0-1.11-.89-2-2-2m0 13H4v-2h16zm0-5H4V5c0-.55.45-1 1-1h14c.55 0 1 .45 1 1z");
}

</style>
