<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ls3drn4je"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:save-copy-20-regular" /></template>
<style>
.ls3drn4je {
  fill: currentColor;
  d: path("M10.5 6.5a.5.5 0 0 1 1 0v2h2a.5.5 0 1 1 0 1h-2v2a.5.5 0 1 1-1 0v-2h-2a.5.5 0 1 1 0-1h2zm5-4.5A2.5 2.5 0 0 1 18 4.5v9a2.5 2.5 0 0 1-2.5 2.5h-9A2.5 2.5 0 0 1 4 13.5v-9A2.5 2.5 0 0 1 6.5 2zM17 4.5A1.5 1.5 0 0 0 15.5 3h-9A1.5 1.5 0 0 0 5 4.5v9A1.5 1.5 0 0 0 6.5 15h9a1.5 1.5 0 0 0 1.5-1.5zM12.5 18c.954 0 1.818-.381 2.45-1H5.5A2.5 2.5 0 0 1 3 14.5V5.05c-.619.632-1 1.496-1 2.45v7A3.5 3.5 0 0 0 5.5 18z");
}

</style>
