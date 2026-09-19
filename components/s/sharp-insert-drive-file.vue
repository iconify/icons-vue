<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ynpw5e4mx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-insert-drive-file" /></template>
<style>
.ynpw5e4mx {
  fill: currentColor;
  d: path("M4.01 2L4 22h16V8l-6-6zM13 9V3.5L18.5 9z");
}

</style>
