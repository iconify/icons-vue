<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3x-w8giv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x3x-w8giv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:sync" /></template>
