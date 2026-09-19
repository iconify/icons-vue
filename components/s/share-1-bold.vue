<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ru5b1fbvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ru5b1fbvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:share-1-bold" /></template>
