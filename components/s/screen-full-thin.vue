<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vwxs6d3ky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vwxs6d3ky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:screen-full-thin" /></template>
