<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dvjv9g5ss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-devices" /></template>
<style>
.dvjv9g5ss {
  fill: currentColor;
  d: path("M4 6h18V4H2v13H0v3h14v-3H4zm20 2h-8v12h8zm-2 9h-4v-7h4z");
}

</style>
