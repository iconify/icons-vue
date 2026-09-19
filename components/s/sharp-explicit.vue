<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y79__c1sa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-explicit" /></template>
<style>
.y79__c1sa {
  fill: currentColor;
  d: path("M21 3H3v18h18zm-6 6h-4v2h4v2h-4v2h4v2H9V7h6z");
}

</style>
