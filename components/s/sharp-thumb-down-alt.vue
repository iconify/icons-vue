<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eig8bhbdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-thumb-down-alt" /></template>
<style>
.eig8bhbdh {
  fill: currentColor;
  d: path("M1 11.6V16h8.31l-1.12 5.38L9.83 23L17 15.82V3H4.69zM19 3h4v12h-4z");
}

</style>
