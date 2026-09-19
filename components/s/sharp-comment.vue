<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kb7knmrfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-comment" /></template>
<style>
.kb7knmrfr {
  fill: currentColor;
  d: path("M21.99 2H2v16h16l4 4zM18 14H6v-2h12zm0-3H6V9h12zm0-3H6V6h12z");
}

</style>
