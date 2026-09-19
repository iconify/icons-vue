<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xdz8jibqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xdz8jibqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:workflow" /></template>
