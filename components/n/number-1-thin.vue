<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s74hacqej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s74hacqej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:number-1-thin" /></template>
