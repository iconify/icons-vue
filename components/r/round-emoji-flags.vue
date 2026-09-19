<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uqizekrtx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-emoji-flags" /></template>
<style>
.uqizekrtx {
  fill: currentColor;
  d: path("M19 9h-5l-.72-1.45c-.17-.34-.52-.55-.9-.55H7V5.72c.6-.34 1-.98 1-1.72c0-1.1-.9-2-2-2s-2 .9-2 2c0 .74.4 1.38 1 1.72V20c0 .55.45 1 1 1s1-.45 1-1v-3h5l.72 1.45a1 1 0 0 0 .89.55H19c.55 0 1-.45 1-1v-8c0-.55-.45-1-1-1m-1 8h-4l-1-2H7V9h5l1 2h5z");
}

</style>
