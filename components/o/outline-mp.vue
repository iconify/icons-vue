<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w9vf0cl5w"/><path class="jor-usn7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-mp" /></template>
<style>
.jor-usn7v {
  fill: currentColor;
  d: path("M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2M5 19V5h14v14z");
}

.w9vf0cl5w {
  fill: currentColor;
  d: path("M17 9h-3.5v6H15v-1.5h2c.55 0 1-.45 1-1V10c0-.55-.45-1-1-1m-.5 3H15v-1.5h1.5zm-5-3H7c-.55 0-1 .45-1 1v5h1.5v-4.5h1v3H10v-3h1V15h1.5v-5c0-.55-.45-1-1-1");
}

</style>
