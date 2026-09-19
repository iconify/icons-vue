<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/ba9j2hbqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ba9j2hbqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:screen-rotation" /></template>
