<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7vx6y1bx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e7vx6y1bx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:search-plus" /></template>
