<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ztu35ibxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ztu35ibxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:more-vertical-square-01" /></template>
