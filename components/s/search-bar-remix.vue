<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nx4qrdfct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nx4qrdfct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:search-bar-remix" /></template>
