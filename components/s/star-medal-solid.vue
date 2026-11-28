<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tv9yuvbgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tv9yuvbgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:star-medal-solid" /></template>
