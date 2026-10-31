<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zfd44acxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zfd44acxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:monitor-play-fill-round" /></template>
