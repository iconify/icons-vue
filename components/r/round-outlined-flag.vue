<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="phhv1wntd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-outlined-flag" /></template>
<style>
.phhv1wntd {
  fill: currentColor;
  d: path("m14 6l-.72-1.45c-.17-.34-.52-.55-.9-.55H6c-.55 0-1 .45-1 1v15c0 .55.45 1 1 1s1-.45 1-1v-6h5l.72 1.45a1 1 0 0 0 .89.55H19c.55 0 1-.45 1-1V7c0-.55-.45-1-1-1zm4 8h-4l-1-2H7V6h5l1 2h5z");
}

</style>
