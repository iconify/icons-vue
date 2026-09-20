<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/woz-1qbwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="woz-1qbwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:text-style" /></template>
