<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wdt8db1ag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:thumb-down-sharp" /></template>
<style>
.wdt8db1ag {
  fill: currentColor;
  d: path("M2 15v-3.17L5.304 4h11.042v11l-6.269 6.192l-.87-.869L10.335 15zm15.346 0V4H21v11z");
}

</style>
