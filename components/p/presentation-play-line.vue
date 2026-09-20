<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zet3uo4bh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zet3uo4bh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:presentation-play-line" /></template>
