<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mro705bga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="mro705bga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:owm-day-804" /></template>
