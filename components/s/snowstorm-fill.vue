<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9it0y2ya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w9it0y2ya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:snowstorm-fill" /></template>
