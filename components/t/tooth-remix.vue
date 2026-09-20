<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nha_vrben.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="nha_vrben"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:tooth-remix" /></template>
