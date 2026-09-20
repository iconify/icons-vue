<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/envibddeq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="envibddeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:medicine-bottle-fill" /></template>
