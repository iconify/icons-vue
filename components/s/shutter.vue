<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hnsns6ogg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hnsns6ogg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:shutter" /></template>
