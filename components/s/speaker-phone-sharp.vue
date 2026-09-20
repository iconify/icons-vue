<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wcz6vpbxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:speaker-phone-sharp" /></template>
<style>
.wcz6vpbxx {
  fill: currentColor;
  d: path("M8.45 8.5L7 7.05q1.025-.975 2.313-1.513T12 5t2.688.538T17 7.05L15.55 8.5q-.725-.725-1.625-1.112T12 7t-1.925.388T8.45 8.5m-2.8-2.9l-1.4-1.4q1.575-1.55 3.563-2.375T12 1t4.188.825T19.75 4.2l-1.4 1.4q-1.275-1.25-2.925-1.925T12 3t-3.425.675T5.65 5.6M8 22V10h8v12z");
}

</style>
