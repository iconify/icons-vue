<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xcup5cekg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xcup5cekg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:rss-square" /></template>
