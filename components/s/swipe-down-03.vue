<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6oj308dp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d6oj308dp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:swipe-down-03" /></template>
