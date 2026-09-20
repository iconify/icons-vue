<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rymd8jx_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rymd8jx_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:talkq" /></template>
